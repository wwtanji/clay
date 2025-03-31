<template>
  <section class="w-full bg-white">
    <div class="max-w-screen-xl mx-auto">
      <div class="grid grid-cols-3 sm:grid-cols-4 md:grid-cols-6 lg:grid-cols-9 gap-y-8 gap-x-6 items-center justify-items-center">
        <div
          v-for="company in companies"
          :key="company.name"
          class="flex flex-col items-center text-center space-y-2 h-16"
        >
          <div class="transition duration-150 flex items-center justify-center h-full">
            <img
              :src="company.logo"
              :alt="company.name"
              class="h-6 object-contain hover:opacity-80"
            />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'CompanyLogos',
  data() {
    return {
      companies: [
        { name: 'Canva', logo: new URL('@/assets/svg/canva.svg', import.meta.url).href },
        { name: 'Hubspot', logo: new URL('@/assets/svg/hubspot.svg', import.meta.url).href },
        { name: 'Vanta', logo: new URL('@/assets/svg/vanta.svg', import.meta.url).href},
        { name: 'Intercom', logo: new URL('@/assets/svg/intercom.svg', import.meta.url).href },
        { name: 'OpenAI', logo: new URL('@/assets/svg/openai.svg', import.meta.url).href},
        { name: 'Square', logo: new URL('@/assets/svg/square.svg', import.meta.url).href },
        { name: 'Retool', logo: new URL('@/assets/svg/retool.svg', import.meta.url).href },
        { name: 'Ramp', logo: new URL('@/assets/svg/ramp.svg', import.meta.url).href },
        { name: 'Anthropic', logo: new URL('@/assets/svg/anthropic.svg', import.meta.url).href},
        { name: 'Rippling', logo: new URL('@/assets/svg/rippling.svg', import.meta.url).href},
        { name: 'Perplexity', logo: new URL('@/assets/svg/perplexity.svg', import.meta.url).href },
        { name: 'Notion', logo: new URL('@/assets/svg/notion.svg', import.meta.url).href },
        { name: 'Webflow', logo: new URL('@/assets/svg/webflow.svg', import.meta.url).href },
        { name: 'Grafana Labs', logo: new URL('@/assets/svg/grafana_labs.svg', import.meta.url).href },
        { name: 'Okta', logo: new URL('@/assets/svg/okta.svg', import.meta.url).href },
        { name: 'Verkada', logo: new URL('@/assets/svg/verkada.svg', import.meta.url).href},
        { name: 'Dropbox', logo: new URL('@/assets/svg/dropbox.svg', import.meta.url).href },
        { name: 'Cursor', logo: new URL('@/assets/svg/cursor.svg', import.meta.url).href }
      ]
    };
  }
});
</script>

<style scoped>
img {
  max-width: 100%;
}
</style>
