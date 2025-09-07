<script setup>
import img_banner from '@/assets/images/img_dashbord_couper.png'
import img_banner_mobile from '@/assets/images/img_dashbord_couper_mobile.png'

// Images section 2
import image1_section_2 from '@/assets/images/img1_section2.png'
import image2_section_2 from '@/assets/images/img2_section2.png'
import image3_section_2 from '@/assets/images/img3_section2.png'

// Images section 3
import image1_section_3 from '@/assets/images/img1_section3.png'
import icon1_section_3 from '@/assets/images/icon1_section3.png'
import icon2_section_3 from '@/assets/images/icon2_section3.png'
import icon3_section_3 from '@/assets/images/icon3_section3.png'

import image_step1 from '@/assets/images/img_step1.png'
import image_step2 from '@/assets/images/img_step2.png'
import image_step3 from '@/assets/images/img_step3.png'

// Image section 4
import image1_section_4 from '@/assets/images/img1_section4.png'

// Avatars
import avatar1 from '@/assets/images/avatar1.png'
import avatar2 from '@/assets/images/avatar2.png'
import avatar3 from '@/assets/images/avatar3.png'


// Images section 7
import image1_section_7 from '@/assets/images/img1_section7.png'
</script>

<template>

  <!-- Bannière -->
  <div class="w-full bg-app-principal bg-no-repeat bg-cover">
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

          <div class="flex flex-col md:flex-row justify-center items-center md:space-x-6 space-y-12 md:space-y-0  w-full">

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

  <!-- Section Beneficts 1 -->
  <div class="px-4 md:px-10 lg:px-16 max-w-7xl mx-auto mt-16  mb-16 p-10" data-aos="fade-up">

    <div class="grid grid-cols-1 lg:grid-cols-6 gap-10 items-center">

      <div class="lg:col-span-2 flex flex-col space-y-4 ">
        <h4 class="block text-[#7C5CFC] font-medium"> WHY USE SPEND.IN </h4>
        <h2 class="text-2xl md:text-5xl font-bold text-black tracking-tight ">Easy, Simple, Affordable</h2>
      </div>

      <p class="lg:col-span-4 lg:w-2/3 text-sm md:text-base">
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
  <!-- Fin Section Beneficts 1 -->

  <!-- Section Beneficts 2 -->
  <div class="px-4 md:px-10 lg:px-16 max-w-7xl mx-auto mt-16  mb-16 p-10" data-aos="fade-up">

    <div class=" flex flex-col md:justify-center md:items-center">

      <div class=" flex flex-col md:justify-center md:items-center space-y-4 mb-10 ">
        <h4 class="block text-[#7C5CFC] font-medium"> WHY USE SPEND.IN </h4>
        <h2 class="text-2xl md:text-5xl font-bold text-black tracking-tight ">Easy, Simple, Affordable</h2>
      </div>

      <p class="max-w-2xl md:text-center text-sm md:text-base ">
        Our platform helps your business in managing expenses. These are some of the reasons why you should use our platform in managing business finances.
      </p>

    </div>

    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-2 gap-10 md:gap-14 mt-14">

      <div class="flex flex-col justify-between space-y-8 lg:w-[80%]">

        <div class="flex items-start space-x-4">
          <img :src="icon1_section_3" alt="" class="h-8">
          <div>
            <h2 class="text-lg  md:text-xl font-semibold text-black tracking-tight mb-2.5 "> Automatic Invoice Payment </h2>
            <p class="text-sm">
              Automatic payments help you to arrange payments on a certain date without doing it manually again.
            </p>
          </div>

        </div>

        <div class="flex items-start space-x-4">
          <img :src="icon2_section_3" alt="" class="h-8">
          <div>
            <h2 class="text-lg  md:text-xl font-semibold text-black tracking-tight mb-2.5 "> Clear payment history </h2>
            <p class="text-sm">
              Clear payment history helps you to track your business expenses on specific dates.
            </p>
          </div>

        </div>

        <div class="flex items-start space-x-4">
          <img :src="icon3_section_3" alt="" class="h-8">
          <div>
            <h2 class="text-lg  md:text-xl font-semibold text-black tracking-tight mb-2.5 "> Use of multi-card payments </h2>
            <p class="text-sm">
              Have more than one debit or credit card? Don't worry, we support payments using more than one card.
            </p>
          </div>

        </div>

      </div>

      <img :src="image1_section_3" alt="" class="h-full object-cover object-center">

    </div>

  </div>
  <!-- Fin Section Beneficts 2 -->

  <!-- Section How tu use 1 -->
  <div class="bg-app-principal py-24 ">
    <div class="px-4 md:px-10 lg:px-16 max-w-7xl mx-auto" data-aos="fade-up">

      <div class=" flex flex-col md:justify-center md:items-center">

      <div class=" flex flex-col md:justify-center md:items-center space-y-4 mb-10 ">
        <h4 class="block text-[#7C5CFC] font-medium"> WHY IT WORKS </h4>
        <h2 class="text-2xl md:text-4xl font-bold tracking-tight text-white">Few Easy Steps and Done</h2>
      </div>

      <p class="max-w-2xl md:text-center text-sm md:text-base ">
        In just few easy step, you are all set to manage your business finances. <br> Manage all expenses with Spend.In all in one place.
      </p>

    </div>

      <div class="grid grid-cols-1 md:grid-cols-3 lg:grid-cols-3 gap-10 md:gap-14 mt-10 w-2/3 md:w-full lg:w-2/3 mx-auto">

        <div class="flex flex-col relative">
          <img :src="image_step1" alt="" class="mb-4 object-center object-cover">
          <span class="absolute top-0 left-0 size-12 flex items-center justify-center rounded-full  bg-app-secondary text-white font-bold -translate-y-6 -translate-x-6 ring-4 ring-app-principal "> 1 </span>
          <h2 class="text-lg font-semibold tracking-tight text-white text-center"> Register your Spend.In account. </h2>
        </div>

        <div class="flex flex-col relative">
          <img :src="image_step2" alt="" class="mb-4 object-center object-cover">
          <span class="absolute top-0 left-0 size-12 flex items-center justify-center rounded-full  bg-app-secondary text-white font-bold -translate-y-6 -translate-x-6 ring-4 ring-app-principal "> 2 </span>
          <h2 class="text-lg font-semibold tracking-tight text-white text-center"> Fill in the list of your business expenses. </h2>
        </div>

        <div class="flex flex-col relative">
          <img :src="image_step3" alt="" class="mb-4 object-center object-cover">
          <span class="absolute top-0 left-0 size-12 flex items-center justify-center rounded-full  bg-app-secondary text-white font-bold -translate-y-6 -translate-x-6 ring-4 ring-app-principal "> 3 </span>
          <h2 class="text-lg font-semibold tracking-tight text-white text-center"> Done, let’s continue the work. </h2>
        </div>

      </div>

      <div class="flex flex-col md:flex-row justify-center items-center md:space-x-6 space-y-12 md:space-y-0  w-full mt-12">

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

    </div>

  </div>
  <!--  Fin Section How tu use 1 -->

  <!-- Section How tu use 2 -->
  <div class="bg-app-principal py-24">
    <div class="px-4 md:px-10 lg:px-16 max-w-7xl mx-auto" data-aos="fade-up">

      <div class="grid grid-cols-1 md:grid-cols-1 lg:grid-cols-2 gap-10 md:gap-14 mt-14">

        <div class="flex flex-col justify-between space-y-8 lg:ml-20 order-1 lg:order-2  ">

          <div class=" flex flex-col">

            <div class=" flex flex-col space-y-4 mb-10 ">
              <h4 class="block text-[#7C5CFC] font-medium"> WHY IT WORKS </h4>
              <h2 class="text-2xl md:text-4xl font-bold tracking-tight text-white">Few Easy Steps and Done</h2>
            </div>

            <p class="max-w-2xl text-sm md:text-base ">
              In just few easy step, you are all set to manage your business finances. Manage all expenses with Spend.In all in one place.
            </p>

          </div>

          <div class="relative">

            <div class="absolute top-0 left-0 w-1 flex h-full items-center justify-center rounded-full  bg-white text-white"> </div>

            <div class="flex flex-col bg-app-gray p-6 rounded-lg">

              <div class="flex items-center space-x-4 pb-5">
                <span class="size-12 flex items-center justify-center rounded-full  bg-app-secondary text-white font-bold"> 1 </span>
                <h2 class="text-lg font-medium tracking-tight text-white">Register your Spend.In account.</h2>
              </div>

             <div class="flex items-center space-x-4 pb-5">
                <span class="size-12 flex items-center justify-center rounded-full  bg-app-secondary text-white font-bold "> 2 </span>
                <h2 class="text-lg font-medium tracking-tight text-white">Fill in the list of your business expenses.</h2>
              </div>

             <div class="flex items-center space-x-4 pb-5">
                <span class="size-12 flex items-center justify-center rounded-full  bg-white font-bold text-black "> 3 </span>
                <h2 class="text-lg font-medium tracking-tight text-white">Done, let’s continue the work.</h2>
              </div>

            </div>

          </div>

        </div>

        <img :src="image1_section_4" alt="" class="h-full object-cover object-center order-2 lg:order-1">

      </div>

    </div>
  </div>
  <!-- Fin Section How tu use 2 -->

  <!-- Section testimonials -->
  <div class="bg-app-principal py-24">
    <div class="px-4 md:px-10 lg:px-16 max-w-7xl mx-auto mt-16  mb-16 p-10" data-aos="fade-up">

      <div class=" flex flex-col md:justify-center md:items-center">

        <div class=" flex flex-col md:justify-center md:items-center space-y-4 mb-10 ">
          <h4 class="block text-[#7C5CFC] font-medium"> WHAT THEY SAY </h4>
          <h2 class="text-2xl md:text-4xl font-bold tracking-tight text-white">Our User Kind Words</h2>
        </div>

        <p class="max-w-2xl md:text-center text-sm md:text-base ">
          Here are some testimonials from our user after using Spend. <br> In to manage their business  expenses.
        </p>

      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10 md:gap-14 mt-10 items-start h-full">

        <div class="flex flex-col justify-between h-full bg-app-gray p-10 shadow-lg rounded-lg">
          <div class="flex flex-col space-y-2 pb-5">
            <h2 class="text-base font-semibold text-white tracking-tight mb-2.5 "> It’s just incredible! </h2>
            <p class="text-sm text-white font-normal opacity-80  ">
              It’s just 1 month since I’m using Spend.In to manage my business expenses, but the result is very satisfying! My business finance now more neat than before, thanks to Spend.In!
            </p>
          </div>

          <div class="flex items-center space-x-6 pt-5 border-t-[2px] border-app-grayText">
            <img :src="avatar1" alt="" class="rounded-xl size-14">
            <div class="flex flex-col space-y-2">
              <h2 class="text-sm font-bold text-white tracking-tight"> Jimmy Bartney </h2>
              <p class="text-xs text-app-grayText"> Product Manager at Picko Lab</p>
            </div>
          </div>
        </div>

        <div class="flex flex-col justify-between h-full bg-app-gray p-10 shadow-lg rounded-lg">
          <div class="flex flex-col space-y-2 pb-5">
            <h2 class="text-base font-semibold text-white tracking-tight mb-2.5 "> Satisfied User Here! </h2>
            <p class="text-sm text-white font-normal opacity-80  ">
              Never thought that with Spend.In managing my business expenses is so easy! Been using this platform for 3 months and still counting!
            </p>
          </div>

          <div class="flex items-center space-x-6 pt-5 border-t-[2px] border-app-grayText">
            <img :src="avatar2" alt="" class="rounded-xl size-14">
            <div class="flex flex-col space-y-2">
              <h2 class="text-sm font-bold text-white tracking-tight"> Natasha Romanoff </h2>
              <p class="text-xs text-app-grayText"> Black Widow </p>
            </div>
          </div>
        </div>

        <div class="flex flex-col justify-between h-full bg-app-gray p-10 shadow-lg rounded-lg">
          <div class="flex flex-col space-y-2 pb-5">
            <h2 class="text-base font-semibold text-white tracking-tight mb-2.5 "> No doubt, Spend.In is the best! </h2>
            <p class="text-sm text-white font-normal opacity-80  ">
              “The best”! That’s what I want to say to this platform, didn’t know that there’s a platform to help you manage your business expenses like this! Very recommended to you who have a big business!
            </p>
          </div>

          <div class="flex items-center space-x-6 pt-5 border-t-[2px] border-app-grayText">
            <img :src="avatar3" alt="" class="rounded-xl size-14">
            <div class="flex flex-col space-y-2">
              <h2 class="text-sm font-bold text-white tracking-tight"> Moritika Kazuki </h2>
              <p class="text-xs text-app-grayText"> Finance Manager at Mangan </p>
            </div>
          </div>
        </div>

      </div>

    </div>

  </div>
  <!-- Fin Section testimonials -->

  <!-- Section download now -->
  <div class="bg-app-principal py-24">
    <div class="px-4 md:px-10 lg:px-16 max-w-7xl mx-auto mt-16  mb-16 p-10" data-aos="fade-up">

      <div class="grid grid-cols-1 md:grid-cols-1 lg:grid-cols-2 gap-10 md:gap-14 mt-10 items-center h-full">

        <div class="flex flex-col">

          <div class=" flex flex-col space-y-4 mb-10 ">
            <h4 class="block text-[#7C5CFC] font-medium"> DOWNLOAD NOW! </h4>
            <h2 class="text-2xl md:text-4xl font-bold tracking-tight text-white">Start Track Your Business Expenses Today</h2>
          </div>

          <p class="max-w-2xl text-sm md:text-base ">
            Are you ready to make your business more organized? <br> Download Spend.In now!
          </p>

          <a href="#" class="mt-10 text-center lg:w-1/3 min-w-max text-sm bg-app-secondary md:w-auto text-white rounded-full transition-all duration-500 ease-in-out px-6 py-3 text-nowrap font-bold">
            Get Free Demo
          </a>

        </div>

        <img :src="image1_section_7" alt="">

      </div>

    </div>

  </div>
  <!-- Fin Section download now -->

</template>

<style>
</style>
