<template>
  <div class="bg-white">
    <app-header></app-header>
    <div class="pt-20 relative">
      <img src="https://cdn.pixabay.com/photo/2018/09/28/19/07/islamic-3710002_960_720.jpg" class="w-full h-full mx-auto" alt=""/>
    </div>
    <div class="absolute text-2xl text-white font-bold top-60 left-40 uppercase">
      <h1>introduction to sadaqa fund</h1>
      <span>daly quote</span>
      <div class="uppercase pt-32">
        <button class="font-semibold text-md py-2 px-9 text-white border-2 bg-green-400 rounded-xl hover:shadow-inner transform hover:scale-105 transition ease-out duration-300">Donate</button>
        <button class="font-semibold text-md py-2 px-9 text-white border-2 bg-green-400 rounded-xl hover:shadow-inner transform hover:scale-105 transition ease-out duration-300">Share</button>
      </div>
      <a id="about"></a>
    </div>
    <div class="my-6">
      <h1 class="uppercase font-bold text-3xl text-center">Milestone / our story</h1>
      <p class="my-6 px-9 text-lg">
        Nigeria has more than 200 million inhabitants and covers 92.4m hectares
        of arable land. About 40% of the population (more than 80million people)
        are smallholder farmers who make a living through agriculture – with a
        total market size of NGN 9 trillion ($25b) annually. However, only about
        25% of smallholder farmers in Nigeria have access to financial services,
        less than 20% of farmers have access to farm extension support, and
        between 40%-60% of food produced goes to waste due to poor links to
        markets. USAIFA International Limited (USAIFA), is a limited liability
        company that leverages Mobile Technology solution to integrate and link
        farmers with most needed services – Micro-Credits, Training and Markets.
        Having understood the agribusiness market and farmer networks in
        Nigeria, we developed a robust ecosystem that provides farmers with
        financial services, extension support and links to produce market using
        mobile value-added services (M-VAS). Our Platform has provided
        micro-credits, training and farm inputs to more than 5,000 farmers in
        Maiduguri & Damboa, Borno State and Karshi, in Nasarawa State. We
        created a network of 562 Farm Sponsors and realized more than N120m
        ($300,000) in revenue from sales of farm produce in 2019. We have
        successfully aggregated 262,000 farmers and secured Mobile Value-Added
        Service (M-VAS) license from the Nigerian Communications Commission. Our
        goal is to aggregate 1,000,000 smallholder farmers by December 2021.
      </p>
    </div>
    <div class="text-center my-20">
      <button
        class="font-semibold uppercase text-md py-4 px-9 text-white border-2 bg-green-400 rounded-xl hover:shadow-inner transform hover:scale-105 transition ease-out duration-300">start a project</button>
    </div>
    <div>
      <h1 class="my-24 underline uppercase font-bold text-3xl text-center">paterners</h1>
      <div class="flex justify-center ">
        <img src="https://donate-ng.com/assets/images/gtb.png" alt="" class="mx-5"/>
        <img src="https://donate-ng.com/assets/images/paystack1.png" alt="" class="mx-5" />
        <img src="https://donate-ng.com/assets/images/afca.png" alt="" class="mx-5" />
        <img src="https://donate-ng.com/assets/images/interswitch.png" alt="" class="mx-5" />
      </div>
    </div>
    <div>
      <a id="contact"></a>
    </div>
    <div class="text-center my-32">
      <h1 class="text-3xl">Need any help? Contact us now!</h1>
      <h2 class="text-2xl">Twocan Solutions</h2>
      <p class="text-xl">2nd Floor Sauda Clinic Complex, Janbulo 2nd Gate, 700241, Kano</p>
      <p>Tel: +2348000000000</p>
      <p>Email: bla-bla-bla@hooli.com</p>
      <div class="flex ml-48">
        <svg xmlns="http://www.w3.org/2000/svg" class="ml-96 w-9 border-current text-green-400" fill="none" viewBox="0 0  24   24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/>
        </svg>
        <h1 class="">Contact Us Now</h1>
      </div>
    </div>
    <app-footer></app-footer>
  </div>
</template>

<script>
import FooterVue from './components/Footer.vue'
import HeaderVue from './components/Header.vue'
export default {
  components: {
    "app-header": HeaderVue,
  "app-footer": FooterVue
  }
}
</script>

<style>
</style>
