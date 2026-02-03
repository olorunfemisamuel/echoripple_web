<script setup lang="ts">

const scrollToTop = () => {
  window.scrollTo({ top: 0, behavior: 'smooth' })
}

</script>

<template>

  <footer class="bg-[#d5d9dc] text-gray-400 font-raleway">

    <!-- Main Footer Content -->
    <div class="max-w-7xl mx-auto px-4 sm:px-6 md:px-20 lg:px-32 xl:px-40 2xl:px-48 py-16 md:py-20">
      <div class="grid grid-cols-1 md:grid-cols-3 gap-12 lg:gap-16">

        <!-- Left: Logo + Description + Socials -->
        <div class="space-y-4">
          <div class="flex items-center gap-2">
            <img src="/Echo Ripple (1).png" alt="EchoRipple" class="h-10 w-auto object-contain scale-400 translate-x-10" />
          </div>
          <p class="text-gray-500 text-sm leading-relaxed max-w-xs">
            Echoripple Studio LLP provides technology services fully focused on creativity and result driven solutions.
          </p>
          <!-- Social Icons -->
          <div class="flex items-center gap-3 pt-2">
            <a href="#" class="w-9 h-9 rounded-full bg-gray-700 hover:bg-[#978395] flex items-center justify-center transition">
             <i class="fa fa-facebook" aria-hidden="true"></i>
            </a>
            <a href="#" class="w-9 h-9 rounded-full bg-gray-700 hover:bg-[#978395] flex items-center justify-center transition">
              <i class="fas fa-linkedin-in text-white text-sm"></i>
            </a>
          </div>
        </div>

        <!-- Middle: Subscribe -->
        <div class="space-y-3">
          <h3 class="font-lince font-bold text-[#978395] text-base">Subscribe</h3>
          <p class="text-gray-300 text-sm">Subscribe to our newsletter for updates</p>
          <div class="flex items-stretch mt-4">
            <input
              type="email"
              placeholder="Enter your email"
              class="flex-1 bg-gray-800 border border-gray-600 text-gray-300 text-sm px-4 py-3 rounded-l-md outline-none focus:border-[#978395] transition placeholder-gray-600"
            />
            <button class="bg-[#978395] hover:bg-[#645162] text-white font-raleway font-semibold text-sm px-6 rounded-r-md transition">
              Subscribe
            </button>
          </div>
        </div>

        <!-- Right: Contact -->
        <div class="space-y-4">
          <h3 class="font-lince font-bold text-[#978395] text-base">Contact</h3>
          <div class="flex items-start gap-3">
            <i class="fas fa-map-marker-alt text-[#978395] mt-1 w-4 text-center"></i>
            <p class="text-gray-500 text-sm leading-relaxed">Kaduna, NG</p>
          </div>
          <div class="flex items-center gap-3">
            <i class="fas fa-phone text-[#978395] w-4 text-center"></i>
            <p class="text-gray-500 text-sm">(+234) 903 098 0577</p>
          </div>
          <div class="flex items-center gap-3">
            <i class="fas fa-envelope text-[#978395] w-4 text-center"></i>
            <p class="text-gray-500 text-sm">info@echoripple.dev</p>
          </div>
        </div>

      </div>
    </div>

    <!-- Divider -->
    <div class="border-t border-gray-700"></div>

    <!-- Bottom Copyright Bar -->
    <div class="max-w-7xl mx-auto px-4 sm:px-6 md:px-20 lg:px-32 xl:px-40 2xl:px-48 py-6 flex items-center justify-center relative">
      <p class="text-gray-600 text-sm text-center">© 2026. All Rights reserved by Echo Ripple</p>

      <!-- Scroll to Top Button -->
      <button
        @click="scrollToTop"
        class="absolute right-4 md:right-20 lg:right-32 xl:right-40 2xl:right-48 -top-5 w-11 h-11 bg-[#978395] hover:bg-[#645162] text-white rounded-md flex items-center justify-center transition shadow-md"
      >
        <span class="font-raleway font-bold text-xs">Top</span>
      </button>
    </div>

  </footer>

</template>