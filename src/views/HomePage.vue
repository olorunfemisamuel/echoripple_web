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
        <h1 class=" font-lince font-bold text-4xl sm:text-4xl md:text-5xl lg:text-6xl xl:text-7xl 2xl:text-8xl text-[#645162] leading-tight">
          Technology Cornerstone <br />
          <span class="text-[#645162]">In Africa</span>
        </h1>

        <p class="text-black text-sm sm:text-base md:text-lg max-w-xl font-raleway font-normal">
          We deliver reliable, scalable, and industry-focused technology services tailored to meet needs across multiple sectors.
        </p>

        <button
          class="bg-[#978395] hover:bg-[#645162] text-black font-raleway font-normal px-6 sm:px-8 py-2.5 sm:py-3 transition text-sm sm:text-base"
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



  <!----Services Section-->
  <section id="services" class="bg-[#1a1a1a] py-16 md:py-24 px-4 sm:px-6 md:px-20 lg:px-32 xl:px-40 2xl:px-48">
    <div class="max-w-7xl mx-auto">

      <!-- Heading -->
      <div class="text-center mb-14">
        <h2 class="font-lince font-bold text-3xl md:text-4xl lg:text-5xl text-white">Services</h2>
        <p class="font-raleway text-[#978395] mt-2 text-sm md:text-base">What We Do</p>
      </div>

      <!-- Cards Grid -->
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6 lg:gap-8">

        <!-- Card 1 -->
        <div class="border border-[#978395] rounded-sm flex flex-col">
          <!-- Image/Icon Area -->
          <div class="flex items-center justify-center h-56 md:h-64 px-6">
            <img src="@/assets/images/SectionImages/webdevIMAGE.jpg" alt="Website Development" class="h-full object-contain" />
          </div>
          <!-- Bottom: Title + Arrow -->
          <div class="flex items-end justify-between px-4 pb-4">
            <h3 class="font-lince font-bold text-[#645162] text-lg md:text-xl leading-tight">Website <br/> Development</h3>
            <button class="w-10 h-10 rounded-full bg-[#978395] hover:bg-[#645162] flex items-center justify-center transition">
              <i class="fas fa-arrow-right text-white text-sm"></i>
            </button>
          </div>
        </div>

        <!-- Card 2 -->
        <div class="border border-[#978395] rounded-sm flex flex-col">
          <div class="flex items-center justify-center h-56 md:h-64 px-6">
            <img src="@/assets/images/SectionImages/webdevIMAGE.jpg" alt="Mobile Development" class="h-full object-contain" />
          </div>
          <div class="flex items-end justify-between px-4 pb-4">
            <h3 class="font-lince font-bold text-[#645162] text-lg md:text-xl leading-tight">Mobile <br/> Development</h3>
            <button class="w-10 h-10 rounded-full bg-[#978395] hover:bg-[#645162] flex items-center justify-center transition">
              <i class="fas fa-arrow-right text-white text-sm"></i>
            </button>
          </div>
        </div>

        <!-- Card 3 -->
        <div class="border border-[#978395] rounded-sm flex flex-col">
          <div class="flex items-center justify-center h-56 md:h-64 px-6">
            <img src="@/assets/images/SectionImages/webdevIMAGE.jpg" alt="Mobile Games" class="h-full object-contain" />
          </div>
          <div class="flex items-end justify-between px-4 pb-4">
            <h3 class="font-lince font-bold text-[#645162] text-lg md:text-xl leading-tight">Mobile <br/> Games</h3>
            <button class="w-10 h-10 rounded-full bg-[#978395] hover:bg-[#645162] flex items-center justify-center transition">
              <i class="fas fa-arrow-right text-white text-sm"></i>
            </button>
          </div>
        </div>

      </div>
    </div>
  </section>


</template>