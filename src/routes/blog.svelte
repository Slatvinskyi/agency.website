<script context="module">
    import Footer from "$lib/Footer.svelte";
    import { fade, fly } from 'svelte/transition';

    export const load = async({fetch}) => {
        const res = await fetch("https://jsonplaceholder.typicode.com/posts")
        const posts = await res.json();
        return {
            props: {
                posts,
    
            },
        };
    };

    let visible = true;
    </script>
    
    <script>
        
          export let posts;
          let searchTerm = "";
          $: searchedPosts = posts.filter((post) =>{
              return post.title.includes(searchTerm) || post.body.includes(searchTerm);
    
          });
             
    </script>

    
    <h1>Posts</h1>
    {#if visible}
	<div in:fly="{{ y: 200, duration: 2000 }}" out:fade>
    
    <input type="text" placeholder="search" bind:value={searchTerm} />
    
    <div class="posts grid grid-cols-2">
    {#if searchedPosts.length}
        {#each searchedPosts as item}       
        
        <div class="shadow bg-white rounded-xl m-20">
            <div class=" bg-size bg-cover bg-center rounded-xl"
                 style="background-image: url('/323.JPG')">
                <div class="p-4 h-32 flex items-end text-white">
                    <h3 class="mb-2">Card Title</h3>
                </div>
            </div>
            <div class="p-4">
                <p class="text-grey-600 text-sm">Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo
                    ligula eget dolor.
                    Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus
                    mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. </p>
                <div class="mt-4">
                    <a sveltekit:prefetch href={`/blog/${item.id}`}>Read more</a>
                </div>
            </div>
          </div>
        
        
        <!--<div class="postbox z-0 m-10 rounded-xl bg-gray-900 relative py-16 px-4  max-w-screen-xl lg:grid lg:grid-cols-2 lg:auto-rows-max lg:gap-x-8 xl:gap-x-12 sm:px-6 sm:py-24 lg:py-32 lg:px-8 shadow-xl">
            <h2>{item.title.substring(0, 20)}</h2>
            <p>{item.body.substring(0, 80)}</p>
            <p class="flex justify-center items-center py-4 px-8 w-auto h-14 text-base font-semibold leading-snug bg-white rounded-full transition ease-in-out duration-250 text-dark-900 hover:text-white focus:outline-none hover:bg-gray-700"><a sveltekit:prefetch href={`/blog/${item.id}`}>Read more</a></p>
        </div>-->
        {/each}
        {:else}
        <p>No posts found with "{searchTerm}"</p>
        {/if}
    </div>
</div>
{/if}
    


   
        <Footer />