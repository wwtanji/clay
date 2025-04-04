<template>
  <section class="bg-white py-24 px-6">
    <div class="max-w-7xl mx-auto flex flex-col lg:flex-row items-center justify-between gap-12">

      <div class="max-w-xl text-center lg:text-left">
        <h2 class="text-4xl sm:text-4xl font-bold text-gray-900 leading-tight">
          Turn data into action with<br />
          flexible, iterable workflows
        </h2>
        <p class="mt-6 text-lg text-gray-600">
          Getting the right data is only half the battle: the real value comes from putting it into action.
          Connect your data to any tool in your tech stack to launch any GTM use case. Iterate and improve quickly.
        </p>

        <div class="mt-8">
          <button class="bg-black text-white text-base font-semibold px-6 py-3 rounded-lg hover:bg-gray-800 transition flex items-center gap-2">
            Start building for free
            <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7"/>
            </svg>
          </button>
        </div>
      </div>

      <div class="flex justify-center lg:justify-end">
        <img
          src="../assets/png/potted-flowers.avif"
          alt="Clay flowers"
          class="w-[320px] sm:w-[360px] lg:w-[400px] h-auto object-contain"
        />
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'ActionWorkflowSection',
});
</script>
