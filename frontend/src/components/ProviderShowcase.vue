<template>
  <section class="bg-blue-600 text-white py-20 px-6 overflow-hidden">
    <div class="max-w-7xl mx-auto flex flex-col lg:flex-row items-center justify-between gap-10">
      <div class="w-full lg:w-1/2">
        <video
          src="@/assets/video/firstvideo.webm"
          autoplay
          muted
          loop
          playsinline
          class="rounded-2xl shadow-xl w-full h-auto"
        ></video>
      </div>

      <div class="w-full lg:w-1/2 max-w-xl space-y-6">
        <h2 class="text-3xl sm:text-4xl font-bold">
          Search 100+ providers for any data point: no contracts needed
        </h2>
        <p class="text-white/90 text-base">
          Complete GTM coverage demands data from multiple premium sources. On Clay,
          connect with vetted data providers for any GTM category—and use your API keys
          with existing providers for free. That includes…
        </p>

        <ul class="space-y-1 text-white font-medium text-base">
          <li>● Contact information</li>
          <li>● Firmographics</li>
          <li>● Technographics</li>
          <li>● Funding information</li>
          <li>● & more</li>
        </ul>

        <div class="flex items-center space-x-4 pt-6">
          <div class="bg-blue-500 rounded-lg px-4 py-2 font-bold text-lg">
            >2x
          </div>
          <p class="text-sm">
            OpenAI more than doubled enrichment<br />
            coverage from low 40% to high 80%
          </p>
        </div>

        <div class="pt-6 border-t border-white/40 flex justify-between items-center">
          <div class="flex items-center space-x-2">
            <img src="@/assets/svg/openai.svg" alt="OpenAI Logo" class="h-5" />
            <span class="text-sm">OpenAI</span>
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
  name: 'ProviderShowcase'
});
</script>

<style scoped>
video {
  max-width: 100%;
  display: block;
}
</style>
