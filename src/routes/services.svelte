<script>
    import { onMount } from 'svelte';
    
    import Footer from "$lib/Footer.svelte";
     
    
    
    let SwipeComponent;
    let SwipeItemComponent;
    
      const swipeConfig = {
        autoplay: true,
        delay: 5000,
        showIndicators: false,
        transitionDuration: 1000,
        defaultIndex: 0,
      };
    
      onMount(async () => {
            const {default: swipe} = await import('svelte-swipe/src/Swipe.svelte');
            const {default: swipeItem} = await import('svelte-swipe/src/SwipeItem.svelte');
            SwipeComponent = swipe;
            SwipeItemComponent = swipeItem;
    });
    </script>
    <style>
      @import url(//db.onlinewebfonts.com/c/9bc5e6e04b0e1b49df457e90788df794?family=Commodore+64);
      @import url(//db.onlinewebfonts.com/c/233fcb19d56aab9a03569180ff42c569?family=Spyware+NBP);
      @import url(//db.onlinewebfonts.com/c/f93192cca3b8d9e3b02337faeb94ab47?family=Retronoid);
      @import url(//db.onlinewebfonts.com/c/44d897600d25364db367f876bb4e2334?family=Biting+My+Nails+Outline);
      
      
      h1 {
        
        font-family: "Commodore 64";
      }
    
      p {
        font-family: "Commodore 64";
      }
    .box{
      box-shadow: 5px 5px 15px 5px #FF8080;
    }
    
    </style>

<div class="swipe-holder w-screen h-96 bg-size bg-cover bg-center rounded-xl mt-0">
    <svelte:component this={SwipeComponent} {...swipeConfig}>
    <svelte:component this={SwipeItemComponent}>
      <img src="/323.JPG" alt="">
    </svelte:component>
  
    <svelte:component this={SwipeItemComponent}>
      <img src="/323.JPG" alt="">
    </svelte:component>
  
    <svelte:component this={SwipeItemComponent}>
      <img src="/323.JPG" alt="">
    </svelte:component>
  </svelte:component>
  </div>


<div class="grid grid-cols-4 m-14 ">
  <div class="p-8 transform -rotate-6 transition hover:scale-105 duration-700 ease-in-out hover:rotate-6">
    <div class="relative bg-black shadow-lg rounded-xl group h-64 w-64 flex justify-center items-center">
      <div class="box rounded-xl h-full w-full absolute z-10 bg-cover bg-center hover:opacity-50 transition-all duration-500 ease-in-out" style="background-image: url('323.JPG')">
      </div>
      <p class="font-bold text-lg text-white absolute z-20 pointer-events-none">
        Video Games
      </p>
    </div>
  </div>
  
  <div class=" p-8 transform -rotate-6 transition hover:scale-105 duration-700 ease-in-out hover:rotate-6">
    <div class="relative bg-black shadow-lg rounded-lg group h-64 w-64 flex justify-center items-center">
      <div class="box rounded-lg h-full w-full absolute z-10 bg-cover bg-center hover:opacity-50 transition-all duration-500 ease-in-out" style="background-image: url('323.JPG')">
      </div>
      <p class="font-bold text-lg text-white absolute z-20 pointer-events-none">
      Audio
      </p>
    </div>
  </div>
  
  <div class="p-8 transform -rotate-6 transition hover:scale-105 duration-700 ease-in-out hover:rotate-6">
    <div class="relative bg-black shadow-lg rounded-lg group h-64 w-64 flex justify-center items-center">
      <div class="box rounded-lg h-full w-full absolute z-10 bg-cover bg-center hover:opacity-50 transition-all duration-500 ease-in-out" style="background-image: url('323.JPG')">
      </div>
      <p class="font-bold text-lg text-white absolute z-20 pointer-events-none">
        Video 
      </p>
    </div>
  </div>
  
  <div class="p-8 transform -rotate-6 transition hover:scale-105 duration-700 ease-in-out hover:rotate-6">
    <div class="relative bg-black shadow-lg rounded-lg group h-64 w-64 flex justify-center items-center">
      <div class="box rounded-lg h-full w-full absolute z-10 bg-cover bg-center hover:opacity-50 transition-all duration-500 ease-in-out" style="background-image: url('323.JPG')">
      </div>
      <p class="font-bold text-lg text-white absolute z-20 pointer-events-none shadow-xl">
        Apps
      </p>
    </div>
  </div>
</div>



<section class="overflow-hidden text-gray-700 m-16">
 <div class="container px-5 py-2 mx-auto lg:pt-24 lg:px-32">
 <div class="flex flex-wrap -m-1 md:-m-2">
     <div class="flex flex-wrap w-1/2">
         <div class="w-1/2 p-1 md:p-2">
             <img alt="gallery" class="block object-cover object-center w-full h-full rounded-lg"
                 src="https://dummyimage.com/500x300/F3F4F7/8693ac">
         </div>
         <div class="w-1/2 p-1 md:p-2">
             <img alt="gallery" class="block object-cover object-center w-full h-full rounded-lg"
                 src="https://dummyimage.com/501x301/F3F4F7/8693ac">
         </div>
         <div class="w-full p-1 md:p-2">
             <img alt="gallery" class="block object-cover object-center w-full h-full rounded-lg"
                 src="https://dummyimage.com/600x360/F3F4F7/8693ac">
         </div>
     </div>
     <div class="flex flex-wrap w-1/2">
         <div class="w-full p-1 md:p-2">
             <img alt="gallery" class="block object-cover object-center w-full h-full rounded-lg"
                 src="https://dummyimage.com/601x361/F3F4F7/8693ac">
         </div>
         <div class="w-1/2 p-1 md:p-2">
             <img alt="gallery" class="block object-cover object-center w-full h-full rounded-lg"
                 src="https://dummyimage.com/502x302/F3F4F7/8693ac">
         </div>
         <div class="w-1/2 p-1 md:p-2">
             <img alt="gallery" class="block object-cover object-center w-full h-full rounded-lg"
                 src="https://dummyimage.com/503x303/F3F4F7/8693ac">
         </div>
     </div>
 </div>
</section>

    
    
    
    
    

    <Footer />