<script setup lang="ts">
import NavbarComponent from '../components/NavbarComponent.vue'
import TitleComponent from '../components/TitleComponent.vue';
import TrustedBySection from '../components/TrustedBySection.vue';
import CompaniesComponent from '../components/CompaniesComponent.vue';
import FuturePillsComponent from '../components/FuturePillsComponent.vue';
import ProviderShowcase from '../components/ProviderShowcase.vue';
import SecondProviderShowcase from '../components/SecondProviderShowcase.vue';
import IntentSignalShowcase from '../components/IntentSignalShowcase.vue';
</script>

<template>
  <main>
    <NavbarComponent/>
    <TitleComponent/>
    <TrustedBySection/>
    <CompaniesComponent/>
    <FuturePillsComponent/>
    <ProviderShowcase/>
    <SecondProviderShowcase/>
    <IntentSignalShowcase/>
  </main>
</template>
