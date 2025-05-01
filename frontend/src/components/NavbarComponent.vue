<template>
  <nav class="w-full bg-white border-b border-gray-200 font-sans">
    <div class="flex items-center justify-between h-20 px-4 md:px-10">
      <div class="flex-shrink-0">
        <a href="#" class="flex items-center">
          <img src="@/assets/logo/claylogoblack.png" alt="Clay Logo" class="h-8 w-auto" />
        </a>
      </div>

      <div class="hidden md:flex flex-1 justify-center">
        <ul class="flex items-center space-x-5 text-gray-900 font-semibold ml-15">
          <li class="relative group">
            <a href="#" class="flex items-center space-x-1 hover:text-gray-700">
              <span>Product</span>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-4 w-4"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
                stroke-width="2">
                <path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7" />
              </svg>
            </a>
          </li>
          <li><a href="#" class="hover:text-gray-700">Solutions</a></li>
          <li><a href="#" class="hover:text-gray-700">Resources</a></li>
          <li><a href="#" class="hover:text-gray-700">Company</a></li>
          <li><a href="#" class="hover:text-gray-700">Enterprise</a></li>
          <li><a href="#" class="hover:text-gray-700">Pricing</a></li>
        </ul>
      </div>

      <div class="hidden md:flex flex-shrink-0 items-center space-x-6">
        <a href="#" class="text-gray-900 hover:text-black font-bold">Get a demo</a>
        <a href="#" class="text-gray-900 hover:text-black font-bold">Login</a>
        <a
          href="#"
          class="inline-flex items-center bg-black text-white px-4 py-2 rounded-lg hover:bg-gray-800 transition duration-200">
          <span class="font-semibold">Sign up</span>
          <svg
            class="ml-2 h-4 w-4"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7" />
          </svg>
        </a>
      </div>

      <div class="md:hidden">
        <button @click="isOpen = !isOpen" class="text-gray-900 focus:outline-none">
          <svg
            v-if="!isOpen"
            xmlns="http://www.w3.org/2000/svg"
            class="h-6 w-6"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor">
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M4 6h16M4 12h16M4 18h16" />
          </svg>
          <svg
            v-else
            xmlns="http://www.w3.org/2000/svg"
            class="h-6 w-6"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor">
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M6 18L18 6M6 6l12 12" />
          </svg>
        </button>
      </div>
    </div>

    <div v-if="isOpen" class="md:hidden px-4 pb-4">
      <ul class="flex flex-col space-y-3 text-gray-900 font-semibold">
        <li><a href="#" class="block hover:text-gray-700">Product</a></li>
        <li><a href="#" class="block hover:text-gray-700">Solutions</a></li>
        <li><a href="#" class="block hover:text-gray-700">Resources</a></li>
        <li><a href="#" class="block hover:text-gray-700">Company</a></li>
        <li><a href="#" class="block hover:text-gray-700">Enterprise</a></li>
        <li><a href="#" class="block hover:text-gray-700">Pricing</a></li>
        <li><a href="#" class="block font-bold">Get a demo</a></li>
        <li><a href="#" class="block font-bold">Login</a></li>
        <li>
          <a
            href="#"
            class="block w-full text-center bg-black text-white px-4 py-2 rounded-lg hover:bg-gray-800 transition duration-200">
            Sign up
          </a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script lang="ts">
import { defineComponent, ref } from 'vue';

export default defineComponent({
  name: 'ClayNavbar',
  setup() {
    const isOpen = ref(false);
    return { isOpen };
  },
});
</script>
