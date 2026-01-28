<script setup lang="ts">
// no logic needed
</script>

<template>
  <!-- 🏠 Hero Section -->
  <section
    id="home"
    class="bg-[#d5d9dc] flex min-h-screen items-center overflow-hidden"
  >
    <div class="max-w-7xl mx-auto w-full px-4 sm:px-6 lg:px-10 py-12 md:py-0 grid grid-cols-1 md:grid-cols-2 gap-8 md:gap-4 items-center">
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
          class="w-full sm:w-[90%] md:w-[110%] lg:w-[120%] xl:w-[130%] 2xl:w-[140%] max-w-none md:relative md:left-5 object-contain"
        />
      </div>
    </div>
  </section>
</template>
