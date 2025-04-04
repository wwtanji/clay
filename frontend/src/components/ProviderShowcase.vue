<template>
  <section class="bg-[#0066e6] text-white py-20 px-6 overflow-hidden">
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
        <h2 class="text-3xl sm:text-4xl font-bold leading-snug">
          Search 100+ providers for any<br />
          data point: no contracts needed
        </h2>

        <p class="text-white/90 text-base">
          Complete GTM coverage demands data from multiple premium sources. On Clay,
          connect with vetted data providers for any GTM category—and use your API keys
          with existing providers for free. That includes…
        </p>

        <ul class="space-y-2">
          <li class="relative pl-5 text-white before:content-['•'] before:absolute before:left-0 before:text-black before:text-xl">
            Contact information
          </li>
          <li class="relative pl-5 text-white before:content-['•'] before:absolute before:left-0 before:text-black before:text-xl">
            Firmographics
          </li>
          <li class="relative pl-5 text-white before:content-['•'] before:absolute before:left-0 before:text-black before:text-xl">
            Technographics
          </li>
          <li class="relative pl-5 text-white before:content-['•'] before:absolute before:left-0 before:text-black before:text-xl">
            Funding information
          </li>
          <li class="relative pl-5 text-white before:content-['•'] before:absolute before:left-0 before:text-black before:text-xl">
            & more
          </li>
        </ul>

        <div class="flex items-center space-x-4 pt-6">
          <div class="bg-white text-[#0066e6] rounded-lg px-4 py-2 font-bold text-lg">
            >2x
          </div>
          <p class="text-sm leading-snug">
            OpenAI more than doubled enrichment<br />
            coverage from low 40% to high 80%
          </p>
        </div>

        <div class="pt-6 border-t border-white/40 flex justify-between items-center">
          <div class="flex items-center space-x-2">
            <img src="../assets/svg/openai.svg" alt="OpenAI Logo" class="h-8" />
            <span class="text-lg font-semibold">OpenAI</span>
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
img {
  max-width: 100%;
  display: block;
}
</style>
