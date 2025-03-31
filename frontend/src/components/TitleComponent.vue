<template>
  <section
    class="relative w-full max-w-[1600px] mx-auto bg-stone-100 rounded-[40px] py-14 sm:py-27 text-center overflow-hidden"
  >
    <div class="px-4 max-w-screen-lg mx-auto">
      <h1 class="text-4xl sm:text-5xl md:text-6xl font-bold text-black leading-tight">
        Go to market with unique data <br> —and the ability to act on it
      </h1>

      <p class="mt-5 text-black text-lg sm:text-xl max-w-3xl mx-auto">
        Access 100+ premium data sources and AI research engines in one platform,
        then automate growth workflows to turn insights into revenue.
      </p>

      <button
        class="mt-8 inline-flex items-center bg-black text-white font-bold px-6 py-3 rounded-md hover:bg-gray-800 transition duration-200"
      >
        Start building for free
        <svg
          class="ml-2 h-5 w-5"
          fill="none"
          stroke="currentColor"
          stroke-width="2"
          viewBox="0 0 24 24"
        >
          <path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7" />
        </svg>
      </button>
    </div>
  </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'HeroSection',
});
</script>

<style scoped>
/* При желании можно добавить кастомные стили здесь */
</style>
