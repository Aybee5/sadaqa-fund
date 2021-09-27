<template>
  <div class="bg-gray-200">
    <app-header></app-header> 
    <div class="pt-20"></div>
    <div class="mt-20 bg-white max-w-md shadow-lg border-2 border-gray-300 max-h-screen mx-auto">
      <div class="mt-5 text-center">
        <h1 class="font-semibold text-4xl my-3 text-gray-600">Login</h1>
        <p class="text-gray-600">New to Sadaqa Fund?<span class="cursor-pointer hover:text-green-400 hover:underline">
            <nuxt-link to="/register" target="/register">Create an account</nuxt-link>
          </span>
        </p>
      </div>
      <div class="pl-10 font-semibold text-gray-500">
        <div class="mt-3 tracking-widest uppercase">
          <label for="email">Email</label>
          <input type="email" placeholder="" class="mt-1 p-3 border-2 outline-none border-gray-300 block w-80 h-10">
        </div>
        <div class="mt-7 tracking-widest uppercase">
          <label for="password">password</label>
          <input type="password" placeholder="" class="mt-1 p-3 border-2 outline-none border-gray-300 block w-80 h-10"/>
        </div>
        <div class="mt-7 flex justify-between">
          <div>
            <input type="checkbox" placeholder="" class="border-2 outline-none w-5 h-5"/>
            <label for="checkbox">Remember me</label>
          </div>
          <div class="text-blue-900 hover:text-green-400 hover:underline mr-20">
            <nuxt-link to="/forget_password" target="/forget_password">Forgot password?</nuxt-link>
          </div>
        </div>
        <button class="font-semibold w-80 my-12 text-md py-2 px-9 text-white border-2 bg-green-400 rounded-xl hover:shadow-inner transform hover:scale-105 transition ease-out duration-300">Login</button>
      </div>
    </div>
    <app-footer></app-footer>    
  </div>
</template>

<script>
import Footer from './components/Footer.vue'
import Header from './components/Header.vue'
export default {
  components: {
    "app-footer": Footer,
    "app-header": Header
  }
}
</script>

<style>
</style>