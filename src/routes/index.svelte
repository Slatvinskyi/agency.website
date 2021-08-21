<script>
import { onMount } from 'svelte';

import Footer from "$lib/Footer.svelte";
 
import Box from '$lib/Box.svelte';

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



<div class="">
<section>
  <div class="bg-gradient-to-r from-gray-900 via-gray-800 to-gray-900">
    <div class="container mx-auto flex flex-col items-center px-4 py-16 pb-24 text-center lg:pb-56 md:py-32 md:px-10 lg:px-32 text-gray-900">
      <h1 class="text-5xl font-bold leading-none sm:text-6xl xl:max-w-3xl text-white">Provident blanditiis cum exercitationem</h1>
      <p class="mt-6 mb-8 text-lg sm:mb-12 xl:max-w-3xl text-coolGray-50">Cupiditate minima voluptate temporibus quia? Architecto beatae esse ab amet vero eaque explicabo!</p>
      <div class="flex flex-wrap justify-center">
        <a class="flex justify-center items-center py-4 px-8 w-auto h-14 text-base font-semibold leading-snug bg-white rounded-full transition ease-in-out duration-250 text-dark-900 hover:text-white focus:outline-none hover:bg-gray-900" href="services">
          Get started
        </a>
        <a class="flex relative justify-center items-center px-8 mt-5 ml-0 w-auto h-14 text-base font-medium leading-snug text-white sm:ml-4 sm:mt-0 group" href="about">
          <span class="block absolute top-0 left-0 w-full h-full bg-gradient-to-r rounded-full transition-all ease-in-out duration-250 from-gray-800 to-gray-900 md:w-14 md:group-hover:w-full"></span>
          <span class="relative ">Learn more</span>
        </a>
      </div>
    </div>
  </div>
  </section>

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

<div class="grid grid-cols-4 m-14">
  <div class="p-8">
    <div class="relative bg-black shadow-lg rounded-xl group h-64 w-64 flex justify-center items-center">
      <div class="rounded-xl h-full w-full absolute z-10 bg-cover bg-center hover:opacity-50 transition-all duration-500 ease-in-out" style="background-image: url('323.JPG')">
      </div>
      <p class="font-bold text-lg text-white absolute z-20 pointer-events-none">
        Video Games
      </p>
    </div>
  </div>
  
  <div class="p-8">
    <div class="relative bg-black shadow-lg rounded-lg group h-64 w-64 flex justify-center items-center">
      <div class="rounded-lg h-full w-full absolute z-10 bg-cover bg-center hover:opacity-50 transition-all duration-500 ease-in-out" style="background-image: url('323.JPG')">
      </div>
      <p class="font-bold text-lg text-white absolute z-20 pointer-events-none">
      Audio
      </p>
    </div>
  </div>
  
  <div class="p-8">
    <div class="relative bg-black shadow-lg rounded-lg group h-64 w-64 flex justify-center items-center">
      <div class="rounded-lg h-full w-full absolute z-10 bg-cover bg-center hover:opacity-50 transition-all duration-500 ease-in-out" style="background-image: url('323.JPG')">
      </div>
      <p class="font-bold text-lg text-white absolute z-20 pointer-events-none">
        Video 
      </p>
    </div>
  </div>
  
  <div class="p-8">
    <div class="relative bg-black shadow-lg rounded-lg group h-64 w-64 flex justify-center items-center">
      <div class="rounded-lg h-full w-full absolute z-10 bg-cover bg-center hover:opacity-50 transition-all duration-500 ease-in-out" style="background-image: url('323.JPG')">
      </div>
      <p class="font-bold text-lg text-white absolute z-20 pointer-events-none shadow-xl">
        Apps
      </p>
    </div>
  </div>
  
  </div>

<div class="flex flex-wrap items-center mt-16">   
  <div class="w-full md:w-5/12 px-4 mr-auto ml-auto">   
       
    <h3 class="text-3xl mb-2 font-semibold leading-normal">Working with us is a pleasure</h3>   
    <p class="text-lg font-light leading-relaxed mt-4 mb-4 text-blueGray-600">Don't let your uses guess by attaching tooltips and popoves to any element. Just make sure you enable them first via JavaScript.</p>    
    <p class="text-lg font-light leading-relaxed mt-0 mb-4 text-blueGray-600">The kit comes with three pre-built pages to help you get started faster. You can change the text and images and you're good to go. Just make sure you enable them first via JavaScript.</p>   
    <a href="https://www.creative-tim.com/learning-lab/tailwind-starter-kit#/presentation" class="font-bold text-blueGray-700 mt-8" target="_blank">Check Tailwind Starter Kit!</a>   
  </div>    
  <div class="w-full md:w-4/12 px-4 mr-auto ml-auto">   
    <div class="relative flex flex-col min-w-0 break-words w-full mb-6 shadow-lg rounded-lg bg-gray-800">   
      <img alt="..." src="/323.JPG" class="w-full align-middle rounded-t-lg">   
      <blockquote class="relative p-8 mb-4">    
        <svg preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 583 95" class="absolute left-0 w-full block" style="height: 95px; top: -94px;">   
          <polygon points="-30,95 583,95 583,65" class="text-gray-800 fill-current"></polygon>    
        </svg>    
        <h4 class="text-xl font-bold text-white">Top Notch Services</h4>    
        <p class="text-md font-light mt-2 text-white">The Arctic Ocean freezes every winter and much of the sea-ice then thaws every summer, and that process will continue whatever happens.</p>   
      </blockquote>   
    </div>    
  </div>    
</div>

<div class="flex flex-wrap m-32"> <div class="lg:pt-12 pt-6 w-full md:w-4/12 px-4 text-center"> <div class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg"> <div class="px-4 py-5 flex-auto"> <div class="text-white p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-red-400"> <i class="fas fa-award"></i> </div> <h6 class="text-xl font-semibold">Awarded Agency</h6> <p class="mt-2 mb-4 text-gray-600"> Divide details about your product or agency work into parts. A paragraph describing a feature will be enough. </p> </div> </div> </div> <div class="w-full md:w-4/12 px-4 text-center"> <div class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg"> <div class="px-4 py-5 flex-auto"> <div class="text-white p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-blue-400"> <i class="fas fa-retweet"></i> </div> <h6 class="text-xl font-semibold">Free Revisions</h6> <p class="mt-2 mb-4 text-gray-600"> Keep you user engaged by providing meaningful information. Remember that by this time, the user is curious. </p> </div> </div> </div> <div class="pt-6 w-full md:w-4/12 px-4 text-center"> <div class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg"> <div class="px-4 py-5 flex-auto"> <div class="text-white p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-green-400"> <i class="fas fa-fingerprint"></i> </div> <h6 class="text-xl font-semibold">Verified Company</h6> <p class="mt-2 mb-4 text-gray-600"> Write a few lines about each one. A paragraph describing a feature will be enough. Keep you user engaged! </p> </div> </div> </div> </div>





<section class="text-gray-600 body-font">
  <div class="container px-5 py-24 mx-auto rounded-xl">
   
    <div class="flex flex-wrap -m-4 rounded-xl">
      <div class="lg:w-1/3 sm:w-1/2 p-4 rounded-xl">
        <div class="flex relative rounded-xl">
          <img alt="gallery" class="rounded-xl absolute inset-0 w-full h-full object-cover object-center" src="https://dummyimage.com/600x360">
          <div class="px-8 py-10 relative z-10 w-full border-4 border-gray-200 bg-white opacity-0 hover:opacity-100">
            <h2 class="tracking-widest text-sm title-font font-medium text-indigo-500 mb-1">THE SUBTITLE</h2>
            <h1 class="title-font text-lg font-medium text-gray-900 mb-3">Shooting Stars</h1>
            <p class="leading-relaxed">Photo booth fam kinfolk cold-pressed sriracha leggings jianbing microdosing tousled waistcoat.</p>
          </div>
        </div>
      </div>
      <div class="lg:w-1/3 sm:w-1/2 p-4">
        <div class="flex relative ">
          <img alt="gallery" class=" rounded-xl absolute inset-0 w-full h-full object-cover object-center" src="https://dummyimage.com/601x361">
          <div class="px-8 py-10 relative z-10 w-full border-4 border-gray-200 bg-white opacity-0 hover:opacity-100">
            <h2 class="tracking-widest text-sm title-font font-medium text-indigo-500 mb-1">THE SUBTITLE</h2>
            <h1 class="title-font text-lg font-medium text-gray-900 mb-3">The Catalyzer</h1>
            <p class="leading-relaxed">Photo booth fam kinfolk cold-pressed sriracha leggings jianbing microdosing tousled waistcoat.</p>
          </div>
        </div>
      </div>
      <div class="lg:w-1/3 sm:w-1/2 p-4">
        <div class="flex relative">
          <img alt="gallery" class="rounded-xl absolute inset-0 w-full h-full object-cover object-center" src="https://dummyimage.com/603x363">
          <div class="px-8 py-10 relative z-10 w-full border-4 border-gray-200 bg-white opacity-0 hover:opacity-100">
            <h2 class="tracking-widest text-sm title-font font-medium text-indigo-500 mb-1">THE SUBTITLE</h2>
            <h1 class="title-font text-lg font-medium text-gray-900 mb-3">The 400 Blows</h1>
            <p class="leading-relaxed">Photo booth fam kinfolk cold-pressed sriracha leggings jianbing microdosing tousled waistcoat.</p>
          </div>
        </div>
      </div>
      <div class="lg:w-1/3 sm:w-1/2 p-4">
        <div class="flex relative">
          <img alt="gallery" class="rounded-xl absolute inset-0 w-full h-full object-cover object-center" src="https://dummyimage.com/602x362">
          <div class="px-8 py-10 relative z-10 w-full border-4 border-gray-200 bg-white opacity-0 hover:opacity-100">
            <h2 class="tracking-widest text-sm title-font font-medium text-indigo-500 mb-1">THE SUBTITLE</h2>
            <h1 class="title-font text-lg font-medium text-gray-900 mb-3">Neptune</h1>
            <p class="leading-relaxed">Photo booth fam kinfolk cold-pressed sriracha leggings jianbing microdosing tousled waistcoat.</p>
          </div>
        </div>
      </div>
      <div class="lg:w-1/3 sm:w-1/2 p-4">
        <div class="flex relative">
          <img alt="gallery" class="rounded-xl absolute inset-0 w-full h-full object-cover object-center" src="https://dummyimage.com/605x365">
          <div class="px-8 py-10 relative z-10 w-full border-4 border-gray-200 bg-white opacity-0 hover:opacity-100">
            <h2 class="tracking-widest text-sm title-font font-medium text-indigo-500 mb-1">THE SUBTITLE</h2>
            <h1 class="title-font text-lg font-medium text-gray-900 mb-3">Holden Caulfield</h1>
            <p class="leading-relaxed">Photo booth fam kinfolk cold-pressed sriracha leggings jianbing microdosing tousled waistcoat.</p>
          </div>
        </div>
      </div>
      <div class="lg:w-1/3 sm:w-1/2 p-4">
        <div class="flex relative">
          <img alt="gallery" class="rounded-xl absolute inset-0 w-full h-full object-cover object-center" src="https://dummyimage.com/606x366">
          <div class="px-8 py-10 relative z-10 w-full border-4 border-gray-200 bg-white opacity-0 hover:opacity-100">
            <h2 class="tracking-widest text-sm title-font font-medium text-indigo-500 mb-1">THE SUBTITLE</h2>
            <h1 class="title-font text-lg font-medium text-gray-900 mb-3">Alper Kamu</h1>
            <p class="leading-relaxed">Photo booth fam kinfolk cold-pressed sriracha leggings jianbing microdosing tousled waistcoat.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
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
    
      
    <p class="mt-6 text-xl text-gray-300"  >
      Anim aute id magna aliqua ad ad non deserunt sunt. Qui irure qui lorem cupidatat commodo. Elit sunt amet fugiat veniam occaecat fugiat aliqua.
    </p>
    
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

<Footer />