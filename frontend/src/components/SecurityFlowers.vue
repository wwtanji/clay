<template>
  <div class="bg-white py-16 px-6 lg:px-12">
    <div class="max-w-7xl mx-auto">
      <div class="text-left mb-14">
        <h2 class="text-4xl font-bold text-gray-900 mb-6 leading-tight">
          Backed by enterprise-grade<br />
          security and scale
        </h2>
        <button
          class="inline-flex items-center px-6 py-3 border border-black text-black rounded-md hover:bg-gray-100 transition text-lg">
          Security at Clay →
        </button>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-4 gap-14 text-center">
        <div v-for="(badge, index) in badges" :key="index">
          <img :src="badge.img" :alt="badge.label" class="mx-auto mb-6 w-57 h-57 object-contain" />
          <h3 class="font-semibold text-xl text-gray-900 mb-2">
            {{ badge.label }}
          </h3>
          <p class="text-base text-gray-600 leading-relaxed max-w-xs mx-auto">
            {{ badge.description }}
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import soc2 from '@/assets/png/SOC2.avif';
import gdpr from '@/assets/png/GDPR.avif';
import ccpa from '@/assets/png/CCPA.avif';
import iso from '@/assets/png/ISO.avif';

const badges = [
  {
    label: 'SOC 2 Type II',
    description: 'We are SOC 2 Type II compliant. Request our SOC 2 in our Trust Center.',
    img: soc2,
  },
  {
    label: 'GDPR',
    description: 'Go to market anywhere in the world — let us handle compliance with local laws.',
    img: gdpr,
  },
  {
    label: 'CCPA',
    description: 'Support your customer base with opt out and DNC support.',
    img: ccpa,
  },
  {
    label: 'ISO 27001 (coming soon)',
    description: 'Securely connect your CRM and other systems.',
    img: iso,
  },
];
</script>
