<script>
   import Footer from  "$lib/Footer.svelte"
</script>
<style>
  @import url(//db.onlinewebfonts.com/c/9bc5e6e04b0e1b49df457e90788df794?family=Commodore+64);
  @import url(//db.onlinewebfonts.com/c/233fcb19d56aab9a03569180ff42c569?family=Spyware+NBP);
  @import url(//db.onlinewebfonts.com/c/f93192cca3b8d9e3b02337faeb94ab47?family=Retronoid);
  @import url(//db.onlinewebfonts.com/c/44d897600d25364db367f876bb4e2334?family=Biting+My+Nails+Outline);
  
  
  h1 {
    
    font-family: "";
  }

  p {
    font-family: "";
  }
.box{
  box-shadow: 5px 5px 15px 5px #FF8080;
}

</style>
<!--Hero-->
<div class="bg-gray-800">
<section>
  <div class="bg-gradient-to-t from-gray-600 via-gray-700 to-gray-900">
    <div class="container mx-auto flex flex-col items-center px-4 py-16 pb-24 text-center lg:pb-56 md:py-32 md:px-10 lg:px-32 text-gray-900">
      <h1 class="text-5xl font-bold leading-none sm:text-6xl xl:max-w-3xl text-white">Wellcome </h1>
      <p class="mt-6 mb-8 text-lg sm:mb-12 xl:max-w-3xl text-white">Cupiditate minima voluptate temporibus quia? Architecto beatae esse ab amet vero eaque explicabo!</p>
      <div class="mt-10 sm:flex sm:justify-center lg:justify-end">
        <a class="flex justify-center items-center py-4 px-8 w-auto h-14 text-base font-semibold leading-snug bg-white rounded-full transition ease-in-out duration-250 text-dark-900 hover:text-white focus:outline-none hover:bg-gray-900" href="services">
          Let's get started
        </a>
        <a class="flex relative justify-center items-center px-8 mt-5 ml-0 w-auto h-14 text-base font-medium leading-snug text-white sm:ml-4 sm:mt-0 group" href="about">
          <span class="block absolute top-0 left-0  w-full h-full bg-gradient-to-r rounded-full transition-all ease-in-out duration-250 from-gray-800 to-gray-900 md:w-14 md:group-hover:w-full"></span>
          <span class="relative">Learn more</span>
        </a>
      </div>
    </div>
  </div>
  </section>
</div>

<div class="">
  <img alt="..." src="https://source.unsplash.com/random/605x350" class="w-7/12  rounded-lg mx-auto mt-16">
  <div class=" -my-56 mx-56">
    <div class="w-full md:w-4/12">   
      <div class="relative flex flex-col min-w-0 break-words w-full mb-6 shadow-lg rounded-lg bg-gray-800 box">   
        <img alt="..." src="https://source.unsplash.com/random/605x350" class="w-full align-middle rounded-t-lg">   
        <blockquote class="relative p-8 mb-4">    
          <svg preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 583 95" class="absolute left-0 w-full block" style="height: 95px; top: -94px;">   
            <polygon points="-30,95 583,95 583,65" class="text-gray-800 fill-current"></polygon>    
          </svg>    
          <h4 class="text-xl font-bold text-white"> Services</h4>    
          <a class="flex relative justify-center items-center px-8 mt-5 ml-0 w-auto h-14 text-base font-medium leading-snug text-white sm:ml-4 sm:mt-0 group" href="about">
            <span class="block absolute top-0 left-0  w-full h-full bg-gradient-to-r rounded-full transition-all ease-in-out duration-250 from-gray-800 to-gray-900 md:w-14 md:group-hover:w-full"></span>
            <span class="relative">Learn more</span>
          </a>   
        </blockquote>   
      </div>    
    </div> 
    </div>
  </div>

<!--Cards-->
<div class="grid grid-cols-3 m-40">
  <div class="wrapper  antialiased text-gray-900  flex h-screen place-items-center mx-auto">
      <div>
          <img src="https://source.unsplash.com/random/350x350" alt=" random imgee" class="w-full object-cover object-center rounded-lg shadow-md">  
       <div class="relative px-4 -mt-16  ">
         <div class="bg-white p-6 rounded-lg shadow-lg">
          <div class="flex items-baseline">
            <span class="bg-teal-200 text-teal-800 text-xs px-2 inline-block rounded-full  uppercase font-semibold tracking-wide">
              lorem
            </span>
            <div class="ml-2 text-gray-600 uppercase text-xs font-semibold tracking-wider">
          Lorem
        </div>  
          </div>
          <h4 class="mt-1 text-xl font-semibold uppercase leading-tight truncate">A random Title</h4>
        <div class="mt-1">
          
          <span class="text-gray-600 text-sm">Text</span>
        </div>
        <div class="mt-4">
          <span class="text-teal-600 text-md font-semibold">Some information </span>
          <span class="text-sm text-gray-600">(text)</span>
        </div>  
        </div>
       </div>
        
     </div>
  </div>
  <div class="wrapper  antialiased text-gray-900  flex h-screen place-items-center mx-auto">
      <div>
          
          <img src="https://source.unsplash.com/random/350x350" alt=" random imgee" class="w-full object-cover object-center rounded-lg shadow-md">    
          
       <div class="relative px-4 -mt-16  ">
         <div class="bg-white p-6 rounded-lg shadow-lg">
          <div class="flex items-baseline">
            <span class="bg-teal-200 text-teal-800 text-xs px-2 inline-block rounded-full  uppercase font-semibold tracking-wide">
              lorem
            </span>
            <div class="ml-2 text-gray-600 uppercase text-xs font-semibold tracking-wider">
          lorem
        </div>  
          </div>
          
          <h4 class="mt-1 text-xl font-semibold uppercase leading-tight truncate">A random Title</h4>
       
        <div class="mt-1">
          text
          <span class="text-gray-600 text-sm">text</span>
        </div>
        <div class="mt-4">
          <span class="text-teal-600 text-md font-semibold">4/5 ratings </span>
          <span class="text-sm text-gray-600">(based on 234 ratings)</span>
        </div>  
        </div>
       </div>
        
     </div>
  </div>
  
  <div class="wrapper  antialiased text-gray-900  flex h-screen place-items-center mx-auto">
      <div>
          
          <img src="https://source.unsplash.com/random/350x350" alt=" random imgee" class="w-full object-cover object-center rounded-lg shadow-md">    
          
       <div class="relative px-4 -mt-16  ">
         <div class="bg-white p-6 rounded-lg shadow-lg">
          <div class="flex items-baseline">
            <span class="bg-teal-200 text-teal-800 text-xs px-2 inline-block rounded-full  uppercase font-semibold tracking-wide">
              lorem
            </span>
            <div class="ml-2 text-gray-600 uppercase text-xs font-semibold tracking-wider">
          2 baths  &bull; 3 rooms
        </div>  
          </div>
          
          <h4 class="mt-1 text-xl font-semibold uppercase leading-tight truncate">A random Title</h4>
       
        <div class="mt-1">
          
          <span class="text-gray-600 text-sm">   /wk</span>
        </div>
        <div class="mt-4">
          <span class="text-teal-600 text-md font-semibold">4/5 ratings </span>
          <span class="text-sm text-gray-600">(based on 234 ratings)</span>
        </div>  
        </div>
       </div>
        
     </div>
  </div>
  </div>




 

<div class="mt-2">
  <img alt="..." src="https://source.unsplash.com/random/605x350" class="w-7/12  rounded-lg mx-auto mt-16">
  <div class="p-8 -my-56 mx-56">
      <div class="relative bg-black shadow-lg rounded-lg group h-64 w-64 flex justify-center items-center">
        <div class="rounded-lg h-full w-full absolute z-10 bg-cover bg-center hover:opacity-50 transition-all duration-500 ease-in-out" style="background-image: url('https://source.unsplash.com/random/350x350')">
        </div>
        <p class="font-bold text-lg text-white absolute z-20 pointer-events-none">
          Video Graphics
        </p>
      </div>
    </div>
  </div>

<section class="text-gray-600 body-font m-44">
  <div class="container px-5 py-24 mx-auto rounded-xl">
   
    <div class="flex flex-wrap -m-4 rounded-xl">
      <div class="lg:w-1/3 sm:w-1/2 p-4 rounded-xl">
        <div class="flex relative rounded-xl">
          <img alt="gallery" class="box rounded-xl absolute inset-0 w-full h-full object-cover object-center" src="https://source.unsplash.com/random/605x350">
          <div class="px-8 py-10 relative z-10 w-full border-4 border-gray-200 bg-white opacity-0 hover:opacity-100">
            <h2 class="tracking-widest text-sm title-font font-medium text-indigo-500 mb-1">THE SUBTITLE</h2>
            <h1 class="title-font text-lg font-medium text-gray-900 mb-3">Shooting Stars</h1>
            <p class="leading-relaxed">Photo booth fam kinfolk cold-pressed sriracha leggings jianbing microdosing tousled waistcoat.</p>
          </div>
        </div>
      </div>
      <div class="lg:w-1/3 sm:w-1/2 p-4">
        <div class="flex relative ">
          <img alt="gallery" class=" rounded-xl absolute inset-0 w-full h-full object-cover object-center" src="https://source.unsplash.com/random/605x350">
          <div class="px-8 py-10 relative z-10 w-full border-4 border-gray-200 bg-white opacity-0 hover:opacity-100">
            <h2 class="tracking-widest text-sm title-font font-medium text-indigo-500 mb-1">THE SUBTITLE</h2>
            <h1 class="title-font text-lg font-medium text-gray-900 mb-3">The Catalyzer</h1>
            <p class="leading-relaxed">Photo booth fam kinfolk cold-pressed sriracha leggings jianbing microdosing tousled waistcoat.</p>
          </div>
        </div>
      </div>
      <div class="lg:w-1/3 sm:w-1/2 p-4">
        <div class="flex relative">
          <img alt="gallery" class="rounded-xl absolute inset-0 w-full h-full object-cover object-center" src="https://source.unsplash.com/random/605x350">
          <div class="px-8 py-10 relative z-10 w-full border-4 border-gray-200 bg-white opacity-0 hover:opacity-100">
            <h2 class="tracking-widest text-sm title-font font-medium text-indigo-500 mb-1">THE SUBTITLE</h2>
            <h1 class="title-font text-lg font-medium text-gray-900 mb-3">The 400 Blows</h1>
            <p class="leading-relaxed">Photo booth fam kinfolk cold-pressed sriracha leggings jianbing microdosing tousled waistcoat.</p>
          </div>
        </div>
      </div>
      <div class="lg:w-1/3 sm:w-1/2 p-4">
        <div class="flex relative">
          <img alt="gallery" class="rounded-xl absolute inset-0 w-full h-full object-cover object-center" src="https://source.unsplash.com/random/605x350">
          <div class="px-8 py-10 relative z-10 w-full border-4 border-gray-200 bg-white opacity-0 hover:opacity-100">
            <h2 class="tracking-widest text-sm title-font font-medium text-indigo-500 mb-1">THE SUBTITLE</h2>
            <h1 class="title-font text-lg font-medium text-gray-900 mb-3">Neptune</h1>
            <p class="leading-relaxed">Photo booth fam kinfolk cold-pressed sriracha leggings jianbing microdosing tousled waistcoat.</p>
          </div>
        </div>
      </div>
      <div class="lg:w-1/3 sm:w-1/2 p-4">
        <div class="flex relative">
          <img alt="gallery" class="rounded-xl absolute inset-0 w-full h-full object-cover object-center" src="https://source.unsplash.com/random/605x350">
          <div class="px-8 py-10 relative z-10 w-full border-4 border-gray-200 bg-white opacity-0 hover:opacity-100">
            <h2 class="tracking-widest text-sm title-font font-medium text-indigo-500 mb-1">THE SUBTITLE</h2>
            <h1 class="title-font text-lg font-medium text-gray-900 mb-3">Holden Caulfield</h1>
            <p class="leading-relaxed">Photo booth fam kinfolk cold-pressed sriracha leggings jianbing microdosing tousled waistcoat.</p>
          </div>
        </div>
      </div>
      <div class="lg:w-1/3 sm:w-1/2 p-4">
        <div class="flex relative">
          <img alt="gallery" class="rounded-xl absolute inset-0 w-full h-full object-cover object-center" src="https://source.unsplash.com/random/605x350">
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

<div class="flex flex-wrap items-center mt-16">   
  <div class="w-full md:w-5/12 px-4 mr-auto ml-auto">   
       
    <h3 class="text-3xl mb-2 font-semibold leading-normal">Working with us is a pleasure</h3>   
    <p class="text-lg font-light leading-relaxed mt-4 mb-4 text-blueGray-600">Don't let your uses guess by attaching tooltips and popoves to any element. Just make sure you enable them first via JavaScript.</p>    
    <p class="text-lg font-light leading-relaxed mt-0 mb-4 text-blueGray-600">The kit comes with three pre-built pages to help you get started faster. You can change the text and images and you're good to go. Just make sure you enable them first via JavaScript.</p>   
    <a href="https://www.creative-tim.com/learning-lab/tailwind-starter-kit#/presentation" class="font-bold text-blueGray-700 mt-8" target="_blank">Check Tailwind Starter Kit!</a>   
  </div>    
  <div class="w-full md:w-4/12 px-4 mr-auto ml-auto ">   
    <div class="relative flex flex-col min-w-0 break-words w-full mb-6 shadow-lg rounded-lg bg-gray-800 box">   
      <img alt="..." src="https://source.unsplash.com/random/605x350" class="w-full align-middle rounded-t-lg">   
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


<div class="container mx-auto px-4 m-16"><div class="items-center flex flex-wrap"><div class="w-full md:w-4/12 ml-auto mr-auto px-4"><img alt="..." class="max-w-full rounded-lg shadow-lg" src="https://source.unsplash.com/random/350x650">
</div><div class="w-full md:w-5/12 ml-auto mr-auto px-4"><div class="md:pr-12"><div class="text-pink-600 p-3 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-pink-300"><i class="fas fa-rocket text-xl"></i></div><h3 class="text-3xl font-semibold">A growing company</h3><p class="mt-4 text-lg leading-relaxed text-blueGray-500">The extension comes with three pre-built pages to help you get started faster. You can change the text and images and you're good to go.</p><ul class="list-none mt-6"><li class="py-2"><div class="flex items-center"><div><span class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-pink-600 bg-pink-200 mr-3"><i class="fas fa-fingerprint"></i></span></div><div><h4 class="text-blueGray-500">Carefully crafted components</h4></div></div></li><li class="py-2"><div class="flex items-center"><div><span class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-pink-600 bg-pink-200 mr-3"><i class="fab fa-html5"></i></span></div><div><h4 class="text-blueGray-500">Amazing page examples</h4></div></div></li><li class="py-2"><div class="flex items-center"><div><span class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-pink-600 bg-pink-200 mr-3"><i class="far fa-paper-plane"></i></span></div><div><h4 class="text-blueGray-500">Dynamic components</h4></div></div></li></ul></div></div></div></div>

<!--He-->
<section class="mx-auto ">
  <div class="container px-5 mx-auto lg:px-24 lg:py-20">
    <div class="flex flex-wrap -m-4">
      <div class="p-4 mx-auto mb-6 lg:w-1/3 lg:mb-0">
        <div class="h-full p-6 text-left bg-blueGray-50 rounded-xl">
          <a class="inline-flex items-center w-full mb-4">
            <img alt="blog" src="https://source.unsplash.com/random/605x350" class="flex-shrink-0 object-cover object-center w-10 h-10 rounded-full">
            <span class="flex flex-col flex-grow pl-3">
              <h2 class="text-xs font-semibold tracking-widest text-black uppercase title-font"> Rasmus Doe <span href="#" class="font-semibold text-blueGray-500 lg:mb-0">Acme's HR </span>
              </h2>
            </span>
          </a>
          <span class="inline-flex justify-start mb-16 sm:mt-0">
            <a class="text-blue-500 hover:text-black">
              <svg fill="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
                <path d="M18 2h-3a5 5 0 00-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 011-1h3z"></path>
              </svg>
            </a>
            <a class="ml-3 text-blue-500 hover:text-black">
              <svg fill="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
                <path d="M23 3a10.9 10.9 0 01-3.14 1.53 4.48 4.48 0 00-7.86 3v1A10.66 10.66 0 013 4s-4 9 5 13a11.64 11.64 0 01-7 2c9 5 20 0 20-11.5a4.5 4.5 0 00-.08-.83A7.72 7.72 0 0023 3z">
                </path>
              </svg>
            </a>
            <a class="ml-3 text-blue-500 hover:text-black">
              <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
                <rect width="20" height="20" x="2" y="2" rx="5" ry="5"></rect>
                <path d="M16 11.37A4 4 0 1112.63 8 4 4 0 0116 11.37zm1.5-4.87h.01"></path>
              </svg>
            </a>
            <a class="ml-3 text-blue-500 hover:text-black">
              <svg fill="currentColor" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="0" class="w-5 h-5" viewBox="0 0 24 24">
                <path stroke="none" d="M16 8a6 6 0 016 6v7h-4v-7a2 2 0 00-2-2 2 2 0 00-2 2v7h-4v-7a6 6 0 016-6zM2 9h4v12H2z">
                </path>
                <circle cx="4" cy="4" r="2" stroke="none"></circle>
              </svg>
            </a>
          </span>
          <p class="text-base font-medium leading-relaxed text-blueGray-700 ">You're about to launch soon and must be 100% focused on your product. Don't loose precious days designing, coding the landing page and testing . </p>
        </div>
      </div>
      <div class="p-4 mx-auto mb-6 lg:w-1/3 lg:mb-0">
        <div class="h-full p-6 text-left bg-blueGray-50 rounded-xl">
          <a class="inline-flex items-center w-full mb-4">
            <img alt="blog" src="https://dummyimage.com/103x103" class="flex-shrink-0 object-cover object-center w-10 h-10 rounded-full">
            <span class="flex flex-col flex-grow pl-3">
              <h2 class="text-xs font-semibold tracking-widest text-black uppercase title-font"> Rasmus Doe <span href="#" class="font-semibold text-blueGray-500 lg:mb-0">Acme's HR </span>
              </h2>
            </span>
          </a>
          <span class="inline-flex justify-start mb-16 sm:mt-0">
            <a class="text-blue-500 hover:text-black">
              <svg fill="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
                <path d="M18 2h-3a5 5 0 00-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 011-1h3z"></path>
              </svg>
            </a>
            <a class="ml-3 text-blue-500 hover:text-black">
              <svg fill="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
                <path d="M23 3a10.9 10.9 0 01-3.14 1.53 4.48 4.48 0 00-7.86 3v1A10.66 10.66 0 013 4s-4 9 5 13a11.64 11.64 0 01-7 2c9 5 20 0 20-11.5a4.5 4.5 0 00-.08-.83A7.72 7.72 0 0023 3z">
                </path>
              </svg>
            </a>
            <a class="ml-3 text-blue-500 hover:text-black">
              <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
                <rect width="20" height="20" x="2" y="2" rx="5" ry="5"></rect>
                <path d="M16 11.37A4 4 0 1112.63 8 4 4 0 0116 11.37zm1.5-4.87h.01"></path>
              </svg>
            </a>
            <a class="ml-3 text-blue-500 hover:text-black">
              <svg fill="currentColor" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="0" class="w-5 h-5" viewBox="0 0 24 24">
                <path stroke="none" d="M16 8a6 6 0 016 6v7h-4v-7a2 2 0 00-2-2 2 2 0 00-2 2v7h-4v-7a6 6 0 016-6zM2 9h4v12H2z">
                </path>
                <circle cx="4" cy="4" r="2" stroke="none"></circle>
              </svg>
            </a>
          </span>
          <p class="text-base font-medium leading-relaxed text-blueGray-700 ">You're about to launch soon and must be 100% focused on your product. Don't loose precious days designing, coding the landing page and testing . </p>
        </div>
      </div>
      <div class="p-4 mx-auto mb-6 lg:w-1/3 lg:mb-0">
        <div class="h-full p-6 text-left bg-blueGray-50 rounded-xl">
          <a class="inline-flex items-center w-full mb-4">
            <img alt="blog" src="https://dummyimage.com/103x103" class="flex-shrink-0 object-cover object-center w-10 h-10 rounded-full">
            <span class="flex flex-col flex-grow pl-3">
              <h2 class="text-xs font-semibold tracking-widest text-black uppercase title-font"> Rasmus Doe <span href="#" class="font-semibold text-blueGray-500 lg:mb-0">Acme's HR </span>
              </h2>
            </span>
          </a>
          <span class="inline-flex justify-start mb-16 sm:mt-0">
            <a class="text-blue-500 hover:text-black">
              <svg fill="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
                <path d="M18 2h-3a5 5 0 00-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 011-1h3z"></path>
              </svg>
            </a>
            <a class="ml-3 text-blue-500 hover:text-black">
              <svg fill="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
                <path d="M23 3a10.9 10.9 0 01-3.14 1.53 4.48 4.48 0 00-7.86 3v1A10.66 10.66 0 013 4s-4 9 5 13a11.64 11.64 0 01-7 2c9 5 20 0 20-11.5a4.5 4.5 0 00-.08-.83A7.72 7.72 0 0023 3z">
                </path>
              </svg>
            </a>
            <a class="ml-3 text-blue-500 hover:text-black">
              <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
                <rect width="20" height="20" x="2" y="2" rx="5" ry="5"></rect>
                <path d="M16 11.37A4 4 0 1112.63 8 4 4 0 0116 11.37zm1.5-4.87h.01"></path>
              </svg>
            </a>
            <a class="ml-3 text-blue-500 hover:text-black">
              <svg fill="currentColor" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="0" class="w-5 h-5" viewBox="0 0 24 24">
                <path stroke="none" d="M16 8a6 6 0 016 6v7h-4v-7a2 2 0 00-2-2 2 2 0 00-2 2v7h-4v-7a6 6 0 016-6zM2 9h4v12H2z">
                </path>
                <circle cx="4" cy="4" r="2" stroke="none"></circle>
              </svg>
            </a>
          </span>
          <p class="text-base font-medium leading-relaxed text-blueGray-700 ">You're about to launch soon and must be 100% focused on your product. Don't loose precious days designing, coding the landing page and testing . </p>
        </div>
      </div>
    </div>
  </div>
</section>
<Footer />