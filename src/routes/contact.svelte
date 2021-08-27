

<script>
import Footer from "$lib/Footer.svelte";
import { fade, fly } from 'svelte/transition';


let visible = true;

</script>

{#if visible}
	<div in:fly="{{ y: 200, duration: 2000 }}" out:fade>
<div class=" py-12 px-4 mx-auto w-6/12 rounded-3xl shadow-xl lg:mr-0 lg:ml-auto bg-gray-700 sm:p-16  lg:p-14 xl:p-16 m-10">

  <!-- Contact form -->
 <form action="https://formsubmit.co/andrii.slatvinskyi@gmail.com" method="POST">
    <div>
      <label for="name" class="ml-0.5 text-gray-300 font-medium text-sm">
        Name *
      </label>
      <input id="name" type="text" name="name" placeholder="John Doe" class="p-4 mt-2 w-full h-14 text-sm font-medium text-white rounded-2xl border-2 border-solid transition duration-200 ease-in-out outline-none bg-gray-800 border-gray-800 focus:border-gray-600 focus:outline-none" required="">
    </div>

    <div class="mt-6">
      <label for="email" class="ml-0.5 text-gray-300 font-medium text-sm">
        Email *
      </label>
      <input id="email" type="email" name="email" placeholder="john@email.com" class="p-4 mt-2 w-full h-14 text-sm font-medium text-white rounded-2xl border-2 border-solid transition duration-200 ease-in-out outline-none bg-gray-800 border-gray-800 focus:border-gray-600 focus:outline-none" required="">
    </div>

    <div class="mt-6">
      <label for="phone" class="ml-0.5 text-gray-300 font-medium text-sm">
        Phone
      </label>
      <input id="phone" type="text" name="phone" placeholder="(123) 456-789" class="p-4 mt-2 w-full h-14 text-sm font-medium text-white rounded-2xl border-2 border-solid transition duration-200 ease-in-out outline-none bg-gray-800 border-gray-800 focus:border-gray-600 focus:outline-none">
    </div>

    <div class="mt-6">
      <label for="message" class="ml-0.5 text-gray-300 font-medium text-sm">
        Message *
      </label>
      <textarea id="message" type="text" name="message" placeholder="Message" rows="5" class="p-4 mt-2 w-full text-sm font-medium text-white rounded-2xl border-2 border-solid transition duration-200 ease-in-out outline-none bg-gray-800 border-gray-800 focus:border-gray-600 focus:outline-none" required=""></textarea>
    </div>

    <div class="flex justify-start mt-6">
      <button type="submit" class="flex justify-center items-center py-4 px-8 w-auto h-14 text-base font-semibold leading-snug bg-white rounded-full transition ease-in-out duration-250 text-gray-900 hover:text-white focus:outline-none hover:bg-gray-900">
        Send message
      </button>
    </div>
  </form>
</div>
</div>
{/if}

<Footer/>