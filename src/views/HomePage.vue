<script setup lang="ts">
// no logic needed
</script>

<template>
  <!-- 🏠 Hero Section -->
  <section
    id="home"
    class="min-h-screen bg-[#647a85] flex items-center"
  >
    <div
      class="max-w-7xl mx-auto w-full px-6 grid grid-cols-1 md:grid-cols-2 gap-12 items-center"
    >
      <!-- LEFT: Text Content -->
      <div class="text-left">
      <img
       src="@/assets/images/HeroImage/Echo Ripple (1).png"
      class="block h-95 w-auto mb-0 z-10 -mt-50"
      />


       <h1 class="text-4xl md:text-6xl font-extrabold text-gray-300 leading-none mb-4 -mt-30">

         Technology Cornerstone <br />
          <span class="text-[#645162]">In Africa</span>
        </h1>

        <p class="text-gray-400 max-w-md mb-8">
          A full service digital agency focused on creativity and result driven
          solutions.
        </p>

        <button
          class="bg-[#978395] hover:bg-[#645162] text-black font-semibold px-8 py-3 transition"
        >
          Let's Build!
        </button>
      </div>

      <!-- RIGHT: Image / Illustration -->
      <div class="flex justify-center md:justify-end">
        <img
          src="@/assets/images/HeroImage/HeroIllustration.png"
          alt="Hero Illustration"
          class="w-full max-w-xl"
        />
      </div>
    </div>
  </section>
</template>



