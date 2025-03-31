<template>
  <nav class="w-full bg-white border-b border-gray-200 font-sans">
    <div class="flex items-center h-20">
      <div class="flex-shrink-0 ml-10">
        <a href="#" class="flex items-center">
          <img src="@/assets/logo/claylogoblack.png" alt="Clay Logo" class="h-8 w-auto" />
        </a>
      </div>

      <div class="flex-1 flex justify-center">
        <ul class="flex items-center space-x-5 text-gray-900 font-semibold ml-15">
          <li class="relative group">
            <a href="#" class="flex items-center space-x-1 hover:text-gray-700">
              <span>Product</span>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24"
                stroke="currentColor" stroke-width="2">
                <path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7" />
              </svg>
            </a>
          </li>
          <li>
            <a href="#" class="hover:text-gray-700">Solutions</a>
          </li>
          <li>
            <a href="#" class="hover:text-gray-700">Resources</a>
          </li>
          <li>
            <a href="#" class="hover:text-gray-700">Company</a>
          </li>
          <li>
            <a href="#" class="hover:text-gray-700">Enterprise</a>
          </li>
          <li>
            <a href="#" class="hover:text-gray-700">Pricing</a>
          </li>
        </ul>
      </div>

      <div class="flex-shrink-0 flex items-center space-x-6 mr-6">
        <a href="#" class="text-gray-900 hover:text-black font-bold">
          Get a demo
        </a>
        <a href="#" class="text-gray-900 hover:text-black font-bold">
          Login
        </a>
        <a href="#"
          class="inline-flex items-center bg-black text-white px-5 py-3.5 rounded-full hover:bg-gray-800 transition duration-200">
          <span class="font-semibold">Sign up</span>
          <svg class="ml-2 h-4 w-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7" />
          </svg>
        </a>
      </div>
    </div>
  </nav>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'ClayNavbar',
});
</script>
