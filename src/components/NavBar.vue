<script setup lang="ts">
import { ref } from 'vue'

const hamburgerOpen = ref(false)

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
                <!--menu items-->
          <div
  id="mobile-menu"
  class="
    fixed
    flex flex-col
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
    mt-5
  "
  :class="{ hidden: !hamburgerOpen }"
>





                    <a href="" class="mx-3 mt-16 ml-5 hover:text-gray-200">Home</a>
                     <a href="" class="mx-3 ml-5 hover:text-gray-200">About Us</a>
                      <a href="" class="mx-3 ml-5 hover:text-gray-200">Services</a>
                       <a href="" class="mx-3 ml-5 hover:text-gray-200">Industries</a>
                </div>
                <!--menu hamburger responsive-->
              <div
  class="cursor-pointer text-gray-300 text-3xl z-50 px-6"
  id="hamburger"
  @click="hamburgerOpen = !hamburgerOpen"
>
  <!-- Hamburger icon -->
  <div v-if="!hamburgerOpen" class="flex flex-col gap-1">
    <span class="w-6 h-0.75 bg-[#645162] block"></span>
    <span class="w-4 h-0.75 bg-[#645162] block"></span>
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
