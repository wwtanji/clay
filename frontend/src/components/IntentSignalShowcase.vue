<template>
  <section class="overflow-hidden text-white">
    <div class="bg-[#025B3E] px-6 py-20">
      <div class="max-w-7xl mx-auto flex flex-col lg:flex-row items-center justify-between gap-10">
        <div class="w-full lg:w-1/2">
          <div class="bg-[#01432F] rounded-t-lg p-6 shadow-xl relative overflow-hidden">
            <div class="flex flex-col items-center gap-4">
              <img src="../assets/svg/tsunoda.svg" alt="Tsunoda" class="w-[220px] z-30 relative" />
              <img src="../assets/svg/table.svg" alt="Peter" class="w-[220px] z-20 relative -mt-4" />
              <img src="../assets/svg/melissa.svg" alt="Melissa" class="w-[220px] z-10 relative -mt-4" />
            </div>
          </div>


    <div class="bg-white px-6 py-16 rounded-b-4xl">
      <div class="max-w-7xl mx-auto">
        <img
          src="../assets/svg/table-green.svg"
          alt="Clay Table"
          class="rounded-xl w-full h-auto"
        />
      </div>
    </div>
        </div>

        <div class="w-full lg:w-1/2 max-w-xl space-y-6">
          <h2 class="text-3xl sm:text-4xl font-bold leading-tight">
            Time your outreach perfectly<br />
            with real-time intent signals
          </h2>
          <p class="text-white/90 text-base">
            Never miss a buying signal. Automatically track and act on key customer events—constantly.
          </p>

          <ul class="space-y-2 text-white text-base font-medium list-inside">
            <li class="relative pl-5 text-white before:content-['•'] before:absolute before:left-0 before:text-black before:text-xl">
              Reach out to customers who’ve changed jobs</li>
            <li class="relative pl-5 text-white before:content-['•'] before:absolute before:left-0 before:text-black before:text-xl">
              Congratulate customers on promotions</li>
            <li class="relative pl-5 text-white before:content-['•'] before:absolute before:left-0 before:text-black before:text-xl">
              Build lists of companies that just raised funding</li>
            <li class="relative pl-5 text-white before:content-['•'] before:absolute before:left-0 before:text-black before:text-xl">
              Email prospects based on new product news</li>
          </ul>

          <div class="flex flex-col sm:flex-row gap-4 pt-4">
            <div class="bg-[#013b2a] text-white rounded-xl px-5 py-4 font-bold text-lg w-fit">
              3M+
              <p class="text-sm font-normal text-white/80">
                Automated monitoring buying signals from<br />
                3M+ companies to prioritize outreach
              </p>
            </div>
            <div class="bg-[#013b2a] text-white rounded-xl px-5 py-4 font-bold text-lg w-fit">
              5x
              <p class="text-sm font-normal text-white/80">
                Added 200+ demos per month and 5x’d team output
              </p>
            </div>
          </div>

          <div class="pt-8 border-t border-white/30 flex justify-between items-center">
            <div class="flex items-center space-x-2 text-white font-bold text-lg">
              <img src="../assets/svg/cursor.svg" alt="Coverflex Logo" class="h-6" />
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
    </div>


  </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'IntentSignalSection'
});
</script>

<style scoped>
img {
  max-width: 100%;
  display: block;
}
</style>
