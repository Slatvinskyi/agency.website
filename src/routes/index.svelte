<script>
	import Box from '$lib/Box.svelte';
import Type from '$lib/Type.svelte';
import { fade, fly } from 'svelte/transition';
import Footer from "$lib/Footer.svelte";

  
	let visible = true;
</script>


{#if visible}
	<div in:fly="{{ y: 200, duration: 2000 }}" out:fade>
    
		 <Box>
         <!-- Card content text-->
    <div class="  rounded-xl flex flex-col justify-center items-center lg:items-start bg-gradient-to-r from-gray-900 via-gray-800 to-gray-900">
      <h1 class="mx-auto text-2xl font-extrabold text-gray-700 sm:text-5xl md:text-6xl lg:text-5xl xl:text-4xl">
        Let’s make your product a success
      </h1>
      <!--<p class="inline-flex z-30 justify-center items-center py-2 px-6 text-sm font-medium tracking-wide text-white bg-gradient-to-r rounded-r-full rounded-tl-full from-gray-800 to-gray-900">
        Welcome
      </p>-->
      <div class="mx-auto mt-6 w-full max-w-lg text-center lg:text-left lg:max-w-none md:max-w-2xl">
        <Type>
          {#if visible}
        <p class="mt-6 text-xl text-gray-300" in:typewriter >
          Anim aute id magna aliqua ad ad non deserunt sunt. Qui irure qui lorem cupidatat commodo. Elit sunt amet fugiat veniam occaecat fugiat aliqua.
        </p>
        {/if}
      </Type>
      </div>
      <!-- Hero buttons -->
      <div class="mt-10 sm:flex sm:justify-center lg:justify-end">
        <a class="flex justify-center items-center py-4 px-8 w-auto h-14 text-base font-semibold leading-snug bg-white rounded-full transition ease-in-out duration-250 text-dark-900 hover:text-white focus:outline-none hover:bg-gray-900" href="services">
          Let's get started
        </a>
        <a class="flex relative justify-center items-center px-8 mt-5 ml-0 w-auto h-14 text-base font-medium leading-snug text-white sm:ml-4 sm:mt-0 group" href="about">
          <span class="block absolute top-0 left-0 z-10 w-full h-full bg-gradient-to-r rounded-full transition-all ease-in-out duration-250 from-gray-800 to-gray-900 md:w-14 md:group-hover:w-full"></span>
          <span class="relative z-20">Learn more</span>
        </a>
      </div>
    </div>

    <!-- Hero image -->
    <div class="flex justify-center items-center mx-auto mt-12 max-w-xl sm:mt-16 lg:mt-0 lg:max-w-none">
      <img src="/323.JPG" class="object-cover z-30 w-auto h-full rounded-lg shadow-md">
    </div>
     </Box>
  </div>
{/if}

{#if visible}
	<div in:fly="{{ x: 200, duration: 2000 }}" out:fade>

    <Box>
     
    
    </Box>
  </div>
{/if}

{#if visible}
	<div in:fly="{{ y: 200, duration: 2000 }}" out:fade>

    <Box></Box>
  </div>
{/if}

{#if visible}
	<div in:fly="{{ x: 200, duration: 2000 }}" out:fade>

    <Box></Box>
  </div>
{/if}

{#if visible}
	<div in:fly="{{ y: 200, duration: 2000 }}" out:fade>

    <Box></Box>
  </div>
{/if}

<Footer />