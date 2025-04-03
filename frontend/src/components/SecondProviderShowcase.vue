<template>
  <section class="bg-[#861657] text-white py-20 px-6 overflow-hidden">
    <div class="max-w-7xl mx-auto flex flex-col lg:flex-row items-center justify-between gap-10">
      <div class="w-full lg:w-1/2">
        <video
          src="@/assets/video/secondvideo.webm"
          autoplay
          muted
          loop
          playsinline
          class="rounded-3xl shadow-xl w-full h-auto"
        ></video>
      </div>

      <div class="w-full lg:w-1/2 max-w-xl space-y-6">
        <h2 class="text-3xl sm:text-4xl font-bold">
          Get unique data points<br /> with AI research agents
        </h2>
        <p class="text-white/90 text-base">
          Automate manual research at scale to uncover data that traditional providers miss.
          Our agents (with tens of millions of monthly runs!) can:
        </p>

        <ul class="space-y-1 text-white font-medium text-base">
          <li>● Flag fraudulent domains</li>
          <li>● Summarize job posts or financial docs</li>
          <li>● Create lead scoring models</li>
          <li>● Clean and format data</li>
          <li>● Enrich SMBs like hotels, restaurants, auto shops, etc.</li>
        </ul>

        <div class="bg-[#6a0d4d] rounded-xl p-6 border border-white/20">
          <p class="text-sm italic">
            "Clay has substantially automated and simplified our research process, which previously
            required manual work from external contractors."
          </p>
          <p class="text-sm mt-4 font-semibold">Davide Grieco</p>
          <p class="text-sm">Head of Growth, Verkada</p>
        </div>

        <div class="pt-6 border-t border-white/40 flex justify-between items-center">
          <div class="flex items-center space-x-2">
            <img src="@/assets/svg/verkada.svg" alt="Verkada Logo" class="h-10" />
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
  name: 'AIResearchShowcase'
});
</script>

<style scoped>
video {
  max-width: 100%;
  display: block;
}
</style>
