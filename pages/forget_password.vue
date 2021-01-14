<template>
  <div class="bg-gray-200">
    <nav class="flex fixed w-full shadow-lg bg-white z-50">
      <div class="mr-60">
        <img
          src="https://image.freepik.com/free-vector/abstract-s-logo-design_8586-76.jpg"
          class="w-20 ml-28"
          alt=""
        />
      </div>
      <div class="flex pl-96 my-7 text-red-400">
        <div class="flex pr-12 cursor-pointer">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="w-6"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M19 20H5a2 2 0 01-2-2V6a2 2 0 012-2h10a2 2 0 012 2v1m2 13a2 2 0 01-2-2V7m2 13a2 2 0 002-2V9a2 2 0 00-2-2h-2m-4-3H9M7 16h6M7 8h6v4H7V8z"
            />
          </svg>
          <h3 class="">About</h3>
        </div>
        <div class="flex pr-12 cursor-pointer">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="w-6"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"
            />
          </svg>
          <h3 class="">Organisation</h3>
        </div>
        <div class="flex pr-12 cursor-pointer">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="w-6"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M18 9v3m0 0v3m0-3h3m-3 0h-3m-2-5a4 4 0 11-8 0 4 4 0 018 0zM3 20a6 6 0 0112 0v1H3v-1z"
            />
          </svg>
          <h3 class="">
            <nuxt-link to="/register" target="/register">Register</nuxt-link>
            <span>/</span>
            <nuxt-link to="/login" target="/login">Login</nuxt-link>
          </h3>
        </div>
        <div class="flex pr-12 cursor-pointer">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="w-6"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M12 18h.01M8 21h8a2 2 0 002-2V5a2 2 0 00-2-2H8a2 2 0 00-2 2v14a2 2 0 002 2z"
            />
          </svg>
          <h3 class="">Contact Us</h3>
        </div>
      </div>
    </nav>
    <div class="pt-20"></div>
    <div
      class="mt-20 bg-white max-w-xl shadow-lg border-2 border-gray-300 max-h-sm mx-auto"
    >
      <div class="mt-5 text-center">
        <h1 class="font-semibold text-4xl my-3 text-gray-600">
          Password Reset
        </h1>
      </div>
      <div id="cursor-id">
        <ul class="bg-blue-200 mx-4 rounded">
          <button  @click="myFunction" class="delete">x</button>
          <li class="pb-3 px-4">            
            <span class="name">Enter you registered email address and a temporary password will be sent to you </span>            
          </li>
        </ul>
      </div>
      <div class="mt-3 font-semibold text-gray-500 px-2 pl-5">
        <label for="email">Email Address</label>
          <input
            type="email"
            placeholder=""
            class="mt-1 border-2 outline-none border-gray-300 block rounded-xl p-3 w-full h-10"
          />
      </div>
      <button
          class="font-semibold w-80 my-12 ml-32 text-md py-2 px-9 text-white bg-red-400 rounded-xl hover:shadow-inner transform hover:scale-105 transition ease-out duration-300"
        >
        Recover Password
      </button>      
    </div>  
    <div class="bg-red-400 h-96 mt-44">
      <div class="flex justify-around">
        <div class="text-white">
          <h2 class="text-lg uppercase font-bold mt-12">About sadaqah-fund</h2>
          <div class="cursor-pointer">
            <p class="hover:underline">About us</p>
            <p class="hover:underline">Terms of service</p>
            <p class="hover:underline">Privacy & Cookies</p>
            <p class="hover:underline">Media</p>
            <p class="hover:underline">Blog</p>
            <p class="hover:underline">Careers</p>
          </div>
        </div>
        <div class="text-white">
          <h2 class="text-lg uppercase font-bold mt-12">Campign</h2>
          <div class="cursor-pointer">
            <p class="hover:underline">How it works</p>
            <p class="hover:underline">Start your campaign</p>
            <p class="hover:underline">Success Stories</p>
            <p class="hover:underline">FAQ's</p>
          </div>
        </div>
        <div class="text-white">
          <h2 class="text-lg uppercase font-bold mt-12">Charities</h2>
          <div class="cursor-pointer">
            <p class="hover:underline">How it works</p>
            <p class="hover:underline">Charity Registration</p>
            <p class="hover:underline">Charity Login</p>
            <p class="hover:underline">Explore Charities</p>
          </div>
        </div>
        <div class="text-white">
          <h2 class="text-lg uppercase font-bold mt-12">Help</h2>
          <div class="cursor-pointer">
            <p class="hover:underline">Support framework</p>
            <p class="hover:underline">Trust & Security</p>
            <p class="hover:underline">Fees</p>
            <p class="hover:underline">Fundraising Tips</p>
            <p class="hover:underline">Accessibility</p>
            <p class="hover:underline">FAQ's</p>
          </div>
        </div>
      </div>
      <h1 class="text-lg text-white uppercase font-bold text-center">
        sadaqah-fund
      </h1>
      <div class="flex justify-center mt-4">
        <img
          src="https://donate-ng.com/assets/images/facebook.png"
          class="w-20 px-2"
          alt=""
        />
        <img
          src="https://donate-ng.com/assets/images/twitter.png"
          class="w-20 px-2"
          alt=""
        />
        <img
          src="https://donate-ng.com/assets/images/instagram.png"
          class="w-20 px-2"
          alt=""
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
    }
  },
  methods: {
    myFunction(e) {
      var list = document.querySelector('#cursor-id');
        if(e.target.className == 'delete'){
          const li = e.target.parentElement;
          list.removeChild(li);
        }
    }
  }
}
</script>

<style>
</style>