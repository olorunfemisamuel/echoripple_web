<script setup lang="ts">

</script>

<template>



        <!--navbar-->
        <header class="sticky top-0 right-0 left-0 bg-[#647a85] z-10">
          <nav class="flex items-center justify-between px-6">
                <!--logo text-->
<div class="flex items-center gap-2">
                   <img
  src="/HeaderLogo.png"
  alt="EchoRipple"
  class="h-5 md:h-20 w-auto"
/>

                </div>
                <!--menu items-->
               <div class="hidden">
                    <a href="" class="mx-3 hover:text-gray-200">Home</a>
                     <a href="" class="mx-3 hover:text-gray-200">About Us</a>
                      <a href="" class="mx-3 hover:text-gray-200">Services</a>
                       <a href="" class="mx-3 hover:text-gray-200">Industries</a>
                </div>

                <!--login button-->
               <div class="hidden">
                    <a href = "" class="mr-4 py-2 px-3 rounded-lg shadow-sm shadow-gray-500 text-white hover:text-gray-800 hover:bg-gray-200 bg-transparent">Login</a>
                </div>

                <!--menu hamburger responsive-->
                <div class="flex flex-col justify-center gap-2 cursor-pointer" id="hamburger">
                   <span class="w-8 h-0.75 bg-gray-300 block"></span>
                    <span class="w-4 h-0.75 bg-gray-300 block"></span>


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
