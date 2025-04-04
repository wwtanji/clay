<template>
  <section
    class="relative w-full max-w-[1600px] mx-auto bg-stone-100 rounded-[40px] py-14 sm:py-24 text-center overflow-hidden"
  >
    <!-- Content -->
    <div class="relative z-10 px-4 max-w-screen-lg mx-auto">
      <h1 class="text-4xl sm:text-5xl md:text-6xl font-bold text-black leading-tight">
        Go to market with unique data <br />
        —and the ability to act on it
      </h1>

      <p class="mt-5 text-black text-lg sm:text-md max-w-3xl mx-auto">
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

  <div
    class="hidden sm:block absolute left-0 sm:left-[-450px] top-[60%] transform -translate-y-1/2 z-0 overflow-hidden"
  >
    <img
      src="../assets/png/start-flower2.png"
      alt="Flowers Left"
      class="w-[180px] sm:w-[250px] lg:w-[950px] max-w-none"
    />
  </div>

  <div
    class="hidden sm:block absolute right-0 top-[40%] transform -translate-y-1/2 z-0 overflow-hidden w-[400px] sm:w-[600px] lg:w-[800px] pointer-events-none"
  >
    <div class="translate-x-[100px] sm:translate-x-[200px] lg:translate-x-[400px]">
      <img
        src="../assets/png/start-flower1.avif"
        alt="Flowers Right"
        class="w-[150px] sm:w-[250px] lg:w-[900px] max-w-none"
      />
    </div>
  </div>

</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'HeroSection',
});
</script>

<style scoped>
img {
  pointer-events: none;
  user-select: none;
}
</style>
