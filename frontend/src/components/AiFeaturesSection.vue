<template>
  <section class="bg-white py-20 px-6">
    <div class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-8">
      <div class="bg-[#82005E] rounded-[2rem] p-8 text-white flex flex-col">
        <div class="rounded-2xl overflow-hidden mb-6">
          <img
            src="@/assets/video/pink.avif"
            alt="AI Formatting"
            class="w-full h-auto object-cover" />
        </div>
        <p class="uppercase text-sm font-semibold text-white/70 mb-2">AI Formatting</p>
        <h3 class="text-2xl font-bold mb-3">Clean and format data<br />with AI in seconds</h3>
        <p class="text-white/90">
          Use AI to transform any record into the format you need. Concatenate data, ensure
          consistent formatting, and remove extra emojis, symbols, or unnecessary info from lists.
        </p>
      </div>

      <div class="bg-[#0059D1] rounded-[2rem] p-8 text-white flex flex-col">
        <div class="rounded-2xl overflow-hidden mb-6">
          <img
            src="@/assets/png/blue.png"
            alt="AI Conditional Logic"
            class="w-full h-auto object-cover" />
        </div>
        <p class="uppercase text-sm font-semibold text-white/70 mb-2">AI Conditional Logic</p>
        <h3 class="text-2xl font-bold mb-3">
          Run action steps conditionally —<br />no engineering needed
        </h3>
        <p class="text-white/90">
          Conditionally run workflows based on any logic. Use different providers for different
          companies, enrich only your best-fit leads, or build in fallbacks (e.g. looking for
          mobiles only if you don't find emails).
        </p>
      </div>

      <div class="bg-[#005B3E] rounded-[2rem] p-8 text-white flex flex-col">
        <div class="rounded-2xl overflow-hidden mb-6">
          <img
            src="@/assets/video/green.avif"
            alt="CRM Integration Example"
            class="w-full h-auto object-cover" />
        </div>
        <p class="uppercase text-sm font-semibold text-white/70 mb-2">Destinations</p>
        <h3 class="text-2xl font-bold mb-3">
          Constantly update any tool — CRM, email sequencer, website builder, or more
        </h3>
        <p class="text-white/90">
          Push enriched data to your CRM, data warehouse, email tool, website CMS, ad manager, etc—
          on a recurring basis. Use our HTTP API capability to build your own integrations without
          code.
        </p>
      </div>

      <div class="bg-[#F6F6F6] rounded-[2rem] p-8 text-black flex flex-col justify-between">
        <div>
          <p class="text-lg mb-6 leading-relaxed">
            “Clay has helped Anthropic significantly improve our lead enrichment and sales data
            pipelines. We’ve been able to consolidate our tech stack to core essentials, like our
            CRM, Clay, and email tool.”
          </p>
          <p class="font-semibold text-sm">Adam Wall</p>
          <p class="text-sm text-gray-500 mb-8">Head of Revenue Operations at Anthropic</p>

          <div class="flex flex-col gap-10 mb-10">
            <div class="flex items-center gap-4 mt-12">
              <span
                class="bg-[#01432F] text-white font-bold text-md px-3 py-1 sm:px-5 sm:py-2 rounded-md text-center">
                4h/week
              </span>
              <p class="text-sm font-semibold">
                Saved with automating inbound lead enrichment and scoring in Salesforce.
              </p>
            </div>

            <div class="flex gap-4 items-start">
              <span
                class="bg-[#01432F] text-white font-bold text-md px-5 py-2 sm:px-7.5 sm:py-3 rounded-md min-w-[72px] text-center whitespace-nowrap">
                100+
              </span>
              <p class="text-sm leading-snug font-semibold">100+ providers accessed via Clay</p>
            </div>

            <div class="flex gap-4 items-start">
              <span
                class="bg-[#01432F] text-white font-bold text-md px-5 py-2 sm:px-7.5 sm:py-3 rounded-md min-w-[72px] text-center whitespace-nowrap">
                100%
              </span>
              <p class="text-sm leading-snug font-semibold">
                Automated all SFDC opportunity upserts
              </p>
            </div>
          </div>
        </div>

        <div class="flex justify-between items-center border-t border-black-300 pt-6">
          <div class="text-lg font-bold tracking-tight">ANTHROP\C</div>
          <a href="#" class="text-sm font-semibold hover:underline flex items-center gap-1">
            Read case study
            <svg
              class="w-4 h-4"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              viewBox="0 0 24 24">
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
    name: 'FourCardFeatureSection',
  });
</script>
