<template>
  <div>
      <nav class="flex fixed w-full shadow-lg bg-white z-50">
      <div class="mr-24">
        <img src="https://image.freepik.com/free-vector/abstract-s-logo-design_8586-76.jpg" class="w-20 ml-28" alt=""/>
      </div>
      <div class="flex pl-96 my-7 text-green-400">
        <div class="flex pr-12 cursor-pointer">
          <svg xmlns="http://www.w3.org/2000/svg" class="w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 20H5a2 2 0 01-2-2V6a2 2 0 012-2h10a2 2 0 012 2v1m2 13a2 2 0 01-2-2V7m2 13a2 2 0 002-2V9a2 2 0 00-2-2h-2m-4-3H9M7 16h6M7 8h6v4H7V8z"/>
          </svg>
          <h3 class="">About</h3>
        </div>
        <div class="flex pr-12 cursor-pointer">
          <svg xmlns="http://www.w3.org/2000/svg" class="w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"/>
          </svg>
          <nuxt-link to="/organisations" target="/organisations">Organisation</nuxt-link>
        </div>
        <div class="flex pr-12 cursor-pointer">
          <svg xmlns="http://www.w3.org/2000/svg" class="w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M18 9v3m0 0v3m0-3h3m-3 0h-3m-2-5a4 4 0 11-8 0 4 4 0 018 0zM3 20a6 6 0 0112 0v1H3v-1z"/>
          </svg>
          <h3 class="">
            <nuxt-link to="/register" target="/register">Register</nuxt-link>
            <span>/</span>
            <nuxt-link to="/login" target="/login">Login</nuxt-link>
          </h3>
        </div>
        <div class="flex pr-12 cursor-pointer">
          <svg xmlns="http://www.w3.org/2000/svg" class="w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 18h.01M8 21h8a2 2 0 002-2V5a2 2 0 00-2-2H8a2 2 0 00-2 2v14a2 2 0 002 2z"/>
          </svg>
          <h3 class="">Contact Us</h3>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>