<script setup lang="ts">
import { ref } from 'vue'

  const hamburgerOpen = ref(false)

</script>

<template>



        <!--navbar-->
        <header class="sticky top-0 right-0 left-0 bg-[#d5d9dc] z-10">
         <nav class="flex items-center justify-between px-6 h-20">
                <!--logo text-->
<div class="flex items-center gap-2">
                   <img
  src="/Echo Ripple (1).png"
  alt="EchoRipple"
 class="h-30 md:h-45 w-auto object-contain"
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

                <!--login button-->
               <div class="hidden">
                    <a href = "" class="mr-4 py-2 px-3 rounded-lg shadow-sm shadow-gray-500 text-white hover:text-gray-800 hover:bg-gray-200 bg-transparent">Login</a>
                </div>

                <!--menu hamburger responsive-->
              <div
  class="cursor-pointer text-gray-300 text-3xl z-50"
  id="hamburger"
  @click="hamburgerOpen = !hamburgerOpen"
>
  <!-- Hamburger icon -->
  <div v-if="!hamburgerOpen" class="flex flex-col gap-2">
    <span class="w-8 h-0.75 bg-[#645162] block"></span>
    <span class="w-4 h-0.75 bg-[#645162] block"></span>
  </div>

  <!-- Cancel (X) icon -->
  <div v-else class="text-4xl font-light">
    ✕
  </div>
</div>


            </nav>

            <!----Putting Navigation Links into Hamburger Menu-->

    <!-- <div id="mobile-menu" class="hidden max-md:flex flex-col bg-gray-900 text-gray-300 px-6 py-4 space-y-4">
    <a href="" class="hover:text-yellow-500">Home</a>
    <a href="" class="hover:text-yellow-500">About</a>
    <a href="" class="hover:text-yellow-500">Process</a>
    <a href="" class="hover:text-yellow-500">Portfolio</a>
</div> -->


        </header>

</template>

<style scoped>

</style>
