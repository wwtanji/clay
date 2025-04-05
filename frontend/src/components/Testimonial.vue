<template>
  <div class="bg-white py-16 px-6 lg:px-12 max-w-7xl mx-auto">
    <h2 class="text-4xl font-bold text-gray-900 mb-10">
      What our customers say<br />about us…
    </h2>

    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
      <div
        v-for="(testimonial, index) in testimonials"
        :key="index"
        :class="[
          'rounded-lg p-10 text-white flex flex-col justify-between',
          testimonial.bg,
        ]"
      >
        <p class="text-lg leading-relaxed mb-6">"{{ testimonial.quote }}"</p>
        <hr class="border-white/60 mb-4" />
        <div class="flex items-center">
          <img
            v-if="testimonial.avatar"
            :src="testimonial.avatar"
            alt="avatar"
            class="w-12 h-12 rounded object-cover border border-gray-200 mr-4"
          />
          <div>
            <p class="font-semibold text-white leading-none">
              {{ testimonial.name }}
            </p>
            <p class="text-white text-sm opacity-90">
              {{ testimonial.role }}
            </p>
          </div>
          <img
            :src="testimonial.logo"
            alt="logo"
            class="ml-auto h-6 object-contain"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import logoOpenAI from '../assets/svg/openai.svg'
import avatar1 from '../assets/png/1avatar.avif'
import avatar2 from '../assets/png/2avatar.avif'
import avatar3 from '../assets/png/3avatar.avif'
import avatar4 from '../assets/png/4avatar.avif'

export default {
  data() {
    return {
      testimonials: [
        {
          quote: 'In my professional opinion, Clay has one of the most practical and exciting applications of AI, in a decades-old practice that has long been stale.',
          name: 'Keith Jones',
          role: 'GTM Systems Lead, OpenAI',
          logo: logoOpenAI,
          avatar: avatar1,
          bg: 'bg-pink-700',
        },
        {
          quote: "Clay should be an essential pillar of every company's GTM stack, enabling outbound built on the highest quality data foundation possible. Now you can automate hours of manual research so sales teams can focus on selling.",
          name: 'Stevie Case',
          role: 'CRO, Vanta',
          logo: logoOpenAI,
          avatar: avatar2,
          bg: 'bg-green-700',
        },
        {
          quote: 'Clay helped us completely reimagine our outbound motion. It changed how we scale campaigns with precision and quality data.',
          name: 'Sam Carter',
          role: 'VP Growth, ExampleCo',
          logo: logoOpenAI,
          avatar: avatar3,
          bg: 'bg-blue-700',
        },
        {
          quote: 'It’s clear that Clay is not just another sales tool. It’s an AI-powered extension of our GTM brain.',
          name: 'Maya Singh',
          role: 'Director of Sales Ops, BetaCorp',
          logo: logoOpenAI,
          avatar: avatar4,
          bg: 'bg-purple-700',
        },
        {
          quote: 'Clay gives us superpowers in how we prospect and qualify accounts.',
          name: 'Alex Yu',
          role: 'Outbound Lead, ScaleTech',
          logo: logoOpenAI,
          avatar: avatar1,
          bg: 'bg-rose-700',
        },
        {
          quote: 'Our sales playbooks are now dynamic and data-driven thanks to Clay.',
          name: 'Lara Kim',
          role: 'VP of Sales, WavePath',
          logo: logoOpenAI,
          avatar: avatar2,
          bg: 'bg-amber-700',
        },
      ],
    }
  },
}
</script>

<style scoped>
</style>
