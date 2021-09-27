<template>
  <div class="bg-gray-100 pb-12">
    <app-header></app-header>
    <div class="p-20"></div>
    <div class="flex  justify-evenly">
      <div v-on:click="view" class="bg-red-300 w-96 h-96 rounded-xl">
        <div class="flex justify-around">
          <img src="https://image.freepik.com/free-vector/abstract-s-logo-design_8586-76.jpg" alt="" class="w-28 mt-3 rounded-xl">
          <p class="mt-20"> {{ org_name }} </p>
        </div>
        <div class="text-center font-bold text-xl uppercase mt-2"> {{ short_story }} </div>
        <div class="ml-4">
          <p class=""> Nigeria has more than 200 million inhabitants and covers 92.4m hectares
          of arable land. About 40% of the population </p>
          <p class="text-md font-semibold">By Name of Organisation </p>
        </div>
        <div class=" border-b mt-4"></div>
        <div class="pt-2 mt-2 bg-white ml-4 w-80 rounded-xl border-2 border-black"> </div>
        <div class="flex justify-around">
          <div class="">
            <div>₦290,000</div>
            <span class=" font-bold text-sm">donations</span>
          </div>
          <div class="">
            <div>58%</div>
            <span class=" font-bold text-sm">funded</span>
          </div>
          <div class="">
            <div>20</div>
            <span class=" font-bold text-sm">days left</span>
          </div>
       </div>
      </div>
      <div class="bg-green-300  w-96 h-96 rounded-xl"></div>
      <div class="">
        <nuxt-link to="/Add_org" target="/Add_org">
          <button class="font-semibold text-md w-96 h-96 text-white border-2 bg-green-400 rounded-xl hover:shadow-inner transform hover:scale-105 transition ease-out duration-300">Add organisations</button>        
        </nuxt-link>        
      </div>
    </div>
  </div>
</template>

<script>
import Header from './components/Header.vue'
export default {
  components:{
    "app-header": Header
  },
  data(){
    return{
      org_name: "Name of Orginasations",
      short_story: "Little-story",
    }
  }
}
</script>

<style>
</style>