<script setup lang="ts">
// no logic needed
</script>

<template>
  <!-- 🏠 Hero Section -->
 <section
  id="home"
 class="bg-[#d5d9dc] flex min-h-screen md:items-center overflow-hidden"
>

   <div class="max-w-7xl mx-auto w-full px-10 pt-8 md:pt-0 grid grid-cols-1 md:grid-cols-2 items-center">
      <!-- LEFT: Text Content -->
      <div class="text-left">



       <h1 class="text-4xl md:text-6xl font-extrabold text-[#645162] leading-none -mt-17 md:-mt-20 px-20 xl:text-8xl ">

         Technology Cornerstone <br />
          <span class="text-[#645162]">In Africa</span>
        </h1>

        <p class="text-black mb-8 px-20">
        We deliver reliable, scalable, and industry-focused technology services tailored to meet needs across multiple sectors.
        </p>

        <button
          class="bg-[#978395] hover:bg-[#645162] text-black font-semibold px-8 py-3 transition ml-20"
        >
          Let's Build!
        </button>
      </div>

      <!-- RIGHT: Image / Illustration -->
      <div class="flex justify-center md:justify-end items-center -mt-40 md:-mt-14 px-20 xl:px-6 xl:">
        <img
          src="@/assets/images/HeroImage/Heroimge.png"
          alt="Hero Illustration"
          class="w-full md:w-[140%] max-w-none relative left-0 md:left-5 object-contain"
        />
      </div>
    </div>
  </section>
</template>



