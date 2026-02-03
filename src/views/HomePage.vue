<script setup lang="ts">
// no logic needed
</script>

<template>
  <!-- 🏠 Hero Section -->
<section
  id="home"
  class="bg-[#d5d9dc] flex min-h-screen items-center overflow-hidden "
>

    <div class="max-w-7xl mx-auto w-full px-4 sm:px-6 md:px-20 lg:px-32 xl:px-40 2xl:px-48 py-12 md:py-0 grid grid-cols-1 md:grid-cols-2 gap-8 md:gap-8 lg:gap-12 xl:gap-16 items-center">
      <!-- LEFT: Text Content -->
      <div class="text-left space-y-4 sm:space-y-6 md:space-y-8">
        <h1 class="text-3xl sm:text-4xl md:text-5xl lg:text-6xl xl:text-7xl 2xl:text-8xl font-extrabold text-[#645162] leading-tight">
          Technology Cornerstone <br />
          <span class="text-[#645162]">In Africa</span>
        </h1>

        <p class="text-black text-sm sm:text-base md:text-lg max-w-xl">
          We deliver reliable, scalable, and industry-focused technology services tailored to meet needs across multiple sectors.
        </p>

        <button
          class="bg-[#978395] hover:bg-[#645162] text-black font-semibold px-6 sm:px-8 py-2.5 sm:py-3 transition text-sm sm:text-base"
        >
          Let's Build!
        </button>
      </div>

      <!-- RIGHT: Image / Illustration -->
      <div class="flex justify-center md:justify-end items-center mt-8 md:mt-0">
        <img
          src="@/assets/images/HeroImage/Heroimge.png"
          alt="Hero Illustration"
          class="w-full sm:w-[90%] md:w-[110%] lg:w-[115%] xl:w-[120%] 2xl:w-[125%] max-w-none md:relative md:left-8 lg:left-12 xl:left-16 2xl:left-20 object-contain"
        />
      </div>
    </div>
  </section>
</template>

