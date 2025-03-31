<template>
  <section class="bg-white rounded-3xl py-12 sm:py-20 px-6 text-center overflow-visible">
    <div class="max-w-5xl mx-auto pt-8 sm:pt-16 pb-20 flex flex-col-reverse lg:flex-row items-center justify-between gap-10">
      <div class="text-left max-w-xl">
        <h2 class="text-4xl sm:text-5xl font-bold text-black leading-tight">
          Boost your enrichment coverage<br />
          <span class="text-gray-500">—including unique data your competitors miss</span>
        </h2>
        <button
          class="mt-8 inline-flex items-center bg-black text-white font-semibold px-6 py-3 rounded-md hover:bg-gray-800 transition duration-200 cursor-pointer"
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
    </div>
  </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'FeaturePills'
});
</script>

<style scoped>
section {
  box-shadow: none;
}

@media (max-width: 640px) {
  .rounded-3xl {
    border-radius: 1.5rem;
  }

  .text-4xl {
    font-size: 2rem;
  }

  .text-2xl {
    font-size: 1.25rem;
  }
}
</style>
