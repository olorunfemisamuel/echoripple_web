<script setup lang="ts">
import { ref, watch } from 'vue'

const hamburgerOpen = ref(false)

watch(hamburgerOpen, (isOpen) => {
  document.body.classList.toggle('overflow-hidden', isOpen)
})
</script>


<template>



        <!--navbar-->
        <header class="sticky top-0 right-0 left-0 bg-[#d5d9dc] z-10">
         <nav class="flex items-center justify-between h-17 md:h-20">
                <!--logo text-->
<div class="flex items-center gap-2">
                   <img
  src="/Echo Ripple (1).png"
  alt="EchoRipple"
 class="h-30 md:h-35 w-auto object-contain mb-2 xl:"
/>

                </div>

<!-- Backdrop for Background Blur-->
<Transition
  enter-active-class="transition-opacity duration-300"
  enter-from-class="opacity-0"
  enter-to-class="opacity-100"
  leave-active-class="transition-opacity duration-200"
  leave-from-class="opacity-100"
  leave-to-class="opacity-0"
>
  <div
    v-if="hamburgerOpen"
    class="fixed inset-0 bg-black/30 backdrop-blur-sm z-40"
    @click="hamburgerOpen = false"
  ></div>
</Transition>



      <Transition
  enter-active-class="transition duration-300 ease-out"
  enter-from-class="opacity-0 translate-x-full"
  enter-to-class="opacity-100 translate-x-0"
  leave-active-class="transition duration-300 ease-in"
  leave-from-class="opacity-100 translate-x-0"
  leave-to-class="opacity-0 translate-x-full"
>
  <div
    v-if="hamburgerOpen"
    id="mobile-menu"
    class="
      fixed
      top-0
      right-0
      h-screen
      w-72
      bg-[#455a64]
      text-gray-300
      px-6
      py-10
      space-y-6
      z-50
    "
  >
 
 <!---Font Awesome Icons--->
<div
  v-if="hamburgerOpen"
  id="mobile-menu"
  class="fixed top-0 right-0 h-screen w-72 bg-[#455a64] text-gray-300 px-6 py-10 space-y-6 z-50"
>
  <div class="mt-16 space-y-6">
  <a href="" class="flex items-center justify-between pb-3 border-b border-transparent hover:border-[#978395] transition-colors duration-300">
    <span>Home</span>
    <i class="fas fa-home"></i>
  </a>
  <a href="" class="flex items-center justify-between pb-3 border-b border-transparent hover:border-[#978395] transition-colors duration-300">
    <span>About Us</span>
    <i class="fas fa-users"></i>
  </a>
  <a href="" class="flex items-center justify-between pb-3 border-b border-transparent hover:border-[#978395] transition-colors duration-300">
    <span>Services</span>
    <i class="fas fa-briefcase"></i>
  </a>
  <a href="" class="flex items-center justify-between pb-3 border-b border-transparent hover:border-[#978395] transition-colors duration-300">
    <span>Industries</span>
    <i class="fas fa-industry"></i>
  </a>
</div>
</div>
</div>
</Transition>

                <!--menu hamburger responsive-->
              <div
  class="cursor-pointer text-gray-300 text-3xl z-50 px-6"
  id="hamburger"
  @click="hamburgerOpen = !hamburgerOpen"
>
  <!-- Hamburger icon -->
  <div v-if="!hamburgerOpen" class="flex flex-col gap-1">
    <span class="w-10 h-1 bg-[#645162] block"></span>
    <span class="w-6 h-1 bg-[#645162] block"></span>
  </div>

  <!-- Cancel (X) icon -->
  <div v-else class="text-4xl font-light">
    ✕
  </div>
</div>


            </nav>

        </header>

</template>

<style scoped>

</style>
