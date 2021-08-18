<template>
  <div class="bg-white">
    <nav class="flex fixed w-full shadow-lg bg-white z-50">
      <div class="mr-24">
        <img
          src="https://image.freepik.com/free-vector/abstract-s-logo-design_8586-76.jpg"
          class="w-20 ml-28"
          alt=""
        />
      </div>
      <div class="flex pl-96 my-7 text-green-400">
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
          <a href="#about">About</a>
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
          <nuxt-link to="/organisations" target="/organisations">Organisation</nuxt-link>
        </div>
        <div class="flex pr-12 cursor-pointer">
          <nuxt-link to="/register" target="/register">
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
          </nuxt-link>          
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
          <a href="#contact">Contact Us</a>
        </div>
      </div>
    </nav>
    <div class="pt-20 relative">
      <img
        src="https://cdn.pixabay.com/photo/2018/09/28/19/07/islamic-3710002_960_720.jpg"
        class="w-full h-full mx-auto"
        alt=""
      />
    </div>
    <div
      class="absolute text-2xl text-white font-bold top-60 left-40 uppercase"
    >
      <h1>introduction to sadaqa fund</h1>
      <span>daly quote</span>
      <div class="uppercase pt-32">
        <button
          class="font-semibold text-md py-2 px-9 text-white border-2 bg-green-400 rounded-xl hover:shadow-inner transform hover:scale-105 transition ease-out duration-300"
        >
          Donate
        </button>
        <button
          class="font-semibold text-md py-2 px-9 text-white border-2 bg-green-400 rounded-xl hover:shadow-inner transform hover:scale-105 transition ease-out duration-300"
        >
          Share
        </button>
      </div>
      <a id="about"></a>
    </div>
    <div class="my-6">
      <h1 class="uppercase font-bold text-3xl text-center">
        Milestone / our story
      </h1>
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
        class="font-semibold uppercase text-md py-4 px-9 text-white border-2 bg-green-400 rounded-xl hover:shadow-inner transform hover:scale-105 transition ease-out duration-300"
      >
        start a project
      </button>
    </div>
    <div>
      <h1 class="my-24 underline uppercase font-bold text-3xl text-center">
        paterners
      </h1>
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
      <p class="text-xl">
        2nd Floor Sauda Clinic Complex, Janbulo 2nd Gate, 700241, Kano
      </p>
      <p>Tel: +2348000000000</p>
      <p>Email: bla-bla-bla@hooli.com</p>
      <div class="flex ml-48">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="ml-96 w-9 border-current text-green-400"
          fill="none"
          viewBox="0 0  24   24"
          stroke="currentColor"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
          />
        </svg>
        <h1 class="">Contact Us Now</h1>
      </div>
    </div>
    <div class="bg-green-400 h-96 mt-12">
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
      <!-- <div class="bg-green-500 mt-32 pt-6 text-center text-bold text-white">© 2021 HOOLI GAMERS.</div> -->
      <h1 class="text-lg text-white uppercase font-bold text-center">sadaqah-fund</h1>
      <div class="flex justify-center mt-4">
        <img src="https://donate-ng.com/assets/images/facebook.png" class="w-20 px-2" alt="">
        <img src="https://donate-ng.com/assets/images/twitter.png" class="w-20 px-2" alt="">
        <img src="https://donate-ng.com/assets/images/instagram.png" class="w-20 px-2" alt="">
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
</style>
