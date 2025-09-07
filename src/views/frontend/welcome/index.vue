<script setup>
import img_banner from '@/assets/images/img_dashbord_couper.png'
import img_banner_mobile from '@/assets/images/img_dashbord_couper_mobile.png'

// Images section 2
import image1_section_2 from '@/assets/images/img1_section2.png'
import image2_section_2 from '@/assets/images/img2_section2.png'
import image3_section_2 from '@/assets/images/img3_section2.png'
</script>

<template>

  <!-- Bannière -->
  <div class="w-full bg-app-principal  bg-[url('@/assets/images/img_banniere.jpg')] bg-no-repeat bg-cover">
    <div class="px-4 md:px-10 lg:px-16 max-w-7xl mx-auto py-2 h-full">
      <div class="md:px-10 mt-16 md:mt-24" data-aos="fade-up">
        <div class="flex flex-col justify-center items-center w-full space-y-10 z-10">

          <h1 class="text-white text-4xl md:text-5xl lg:text-7xl font-bold text-center lg:max-w-6xl">
            All your business <br>
            expenses in one place.
          </h1>

          <p class="text-base md:text-xl text-center md:max-w-4xl text-app-grayText">
            Your one-stop finance empower platform. <br>
            Manage all your business expenses with our supafast app.
          </p>

          <div class="flex flex-col md:flex-row justify-center items-center w-full md:space-x-6 space-y-12 md:space-y-0  w-full">

            <div>
              <a href="#" class=" text-sm bg-app-secondary w-full md:w-auto text-white rounded-full transition-all duration-500 ease-in-out px-6 py-3 text-nowrap font-bold">
                Get Free Demo
              </a>
            </div>

            <div class="">
              <a href="#" class="text-white bg-app-gray text-sm font-bold rounded-full transition-all duration-500 ease-in-out px-6 py-3 text-nowrap">
               See Pricing
              </a>
            </div>

          </div>

          <div class="pt-0 translate-y-10 index">
            <img :src="img_banner" alt="Une image" class="w-auto hidden md:block">
            <img :src="img_banner_mobile" alt="Une image" class=" md:hidden">
          </div>

        </div>
      </div>
    </div>
  </div>
  <!-- Fin Bannière -->

  <!-- Section 1 -->
  <div class="px-4 md:px-10 lg:px-16 max-w-7xl mx-auto mt-24 mb-24 p-10 ">

    <div class="grid grid-cols-1 lg:grid-cols-6 gap-10 items-center">

      <div class="lg:col-span-2 flex flex-col space-y-4 ">
        <h4 class="block text-[#7C5CFC] font-medium"> WHY USE SPEND.IN </h4>
        <h2 class="text-2xl md:text-5xl font-bold text-black tracking-tight ">Easy, Simple, Affordable</h2>
      </div>

      <p class="lg:col-span-4 lg:w-2/3">
        Our platform helps your business in managing expenses. These are some of the reasons why you should use our platform in managing business finances.
      </p>

    </div>

    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10 md:gap-14 mt-10">

      <div class="flex flex-col">
        <img :src="image1_section_2" alt="" class="mb-4">
        <div>
          <h2 class="text-lg  md:text-xl font-semibold text-black tracking-tight mb-2.5 "> Automatic Invoice Payment </h2>
          <p class="text-sm">
            No need to pay manually, we provide automatic invoice payment service! Set a payment schedule and you're done, it's that easy!
          </p>
        </div>
      </div>

      <div class="flex flex-col">
        <img :src="image2_section_2" alt="" class="mb-4">
        <div>
          <h2 class="text-lg  md:text-xl font-semibold text-black tracking-tight mb-2.5 "> Clear payment history </h2>
          <p class="text-sm">
            Still writing manual expenses? Our platform breaks down every expense you log down to the  millisecond!
          </p>
        </div>
      </div>

      <div class="flex flex-col">
        <img :src="image3_section_2" alt="" class="mb-4">
        <div>
          <h2 class="text-lg  md:text-xl font-semibold text-black tracking-tight mb-2.5 "> Use of multi-card payments </h2>
          <p class="text-sm">
            Have more than 1 bank account or credit/debit card? Our platform is already integrated with many banks around the world, for easier payments!
          </p>
        </div>
      </div>

    </div>

  </div>
  <!-- Fin Section 1 -->

</template>

<style>
.index {
  z-index: -1
}
</style>
