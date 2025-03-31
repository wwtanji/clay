<template>
  <section class="bg-[#025B3E] text-white py-20 px-6 overflow-hidden relative">
    <div class="max-w-7xl mx-auto flex flex-col lg:flex-row items-center justify-between gap-10">
      <div class="w-full lg:w-1/2 relative">
        <img
          src="@/assets/svg/tsunoda.svg"
          alt="Table Background"
          class="rounded-xl w-full h-auto"
        />
      </div>

      <div class="w-full lg:w-1/2 max-w-xl space-y-6">
        <h2 class="text-3xl sm:text-4xl font-bold">
          Time your outreach perfectly<br />
          with real-time intent signals
        </h2>
        <p class="text-white/90 text-base">
          Never miss a buying signal. Automatically track and act on key customer events—constantly.
        </p>

        <ul class="space-y-1 text-white font-medium text-base">
          <li>● Reach out to customers who’ve changed jobs</li>
          <li>● Congratulate customers on promotions</li>
          <li>● Build lists of companies that just raised funding</li>
          <li>● Email prospects based on new product news</li>
        </ul>

        <div class="flex flex-col sm:flex-row gap-4 pt-6">
          <div class="bg-white text-black rounded-lg px-5 py-3 font-bold text-lg w-fit">
            3M+
            <p class="text-sm font-normal">companies tracked</p>
          </div>
          <div class="bg-white text-black rounded-lg px-5 py-3 font-bold text-lg w-fit">
            5x
            <p class="text-sm font-normal">team efficiency</p>
          </div>
        </div>

        <div class="pt-6 border-t border-white/40 flex justify-between items-center">
          <div class="flex items-center space-x-2">
            <span class="text-sm">coverflex</span>
          </div>
          <a href="#" class="inline-flex items-center text-white font-semibold hover:underline">
            Read case study
            <svg
              class="ml-1 h-4 w-4"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              viewBox="0 0 24 24"
            >
              <path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7" />
            </svg>
          </a>
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'IntentSignalShowcase'
});
</script>

<style scoped>
img {
  max-width: 100%;
  display: block;
}
</style>
