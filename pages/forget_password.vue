<template>
  <div class="bg-gray-200">
    <app-header></app-header>
    <div class="pt-20"></div>
    <div class="mt-20 bg-white max-w-xl shadow-lg border-2 border-gray-300 max-h-sm mx-auto">
      <div class="mt-5 text-center">
        <h1 class="font-semibold text-4xl my-3 text-gray-600">Password Reset</h1>
      </div>
      <div id="cursor-id">
        <ul class="bg-blue-200 mx-4 rounded">
          <button  @click="ignore" class="delete">x</button>
          <li class="pb-3 px-4">            
            <span class="name">Enter you registered email address and a temporary password will be sent to you </span>            
          </li>
        </ul>
      </div>
      <div class="mt-3 font-semibold text-gray-500 px-2 pl-5">
        <label for="email">Email Address</label>
          <input type="email"
            placeholder="" class="mt-1 border-2 outline-none border-gray-300 block rounded-xl p-3 w-full h-10"/>
      </div>
      <button class="font-semibold w-80 my-12 ml-32 text-md py-2 px-9 text-white bg-green-400 rounded-xl hover:shadow-inner transform hover:scale-105 transition ease-out duration-300">
        Recover Password
      </button>      
    </div>  
    <app-footer></app-footer>
  </div>
</template>

<script>
import Footer from './components/Footer.vue';
import Header from './components/Header.vue';
export default {
  components:{
    "app-header":Header,
    "app-footer": Footer
  },
  data() {
    return {
    }
  },
  methods: {
    ignore(e) {
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