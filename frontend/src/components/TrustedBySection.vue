<template>
<section class="py-8 text-center">
    <h2 class="text-xs uppercase font-bold text-black tracking-wide">
        TRUSTED BY MORE THAN 300,000 LEADING GTM TEAMS OF ALL SIZES
    </h2>

    <div class="flex justify-center items-center space-x-6 mt-4">
        <div class="flex items-center space-x-2 text-gray-600">
            <img src="@/assets/google.svg" alt="Google logo" class="w-5 h-5" />
        </div>

        <div class="flex items-center space-x-2 text-gray-600">
            <div class="flex items-center space-x-1">
                <svg v-for="i in 5" :key="i" class="w-5 h-5 text-gray-500" fill="currentColor" viewBox="0 0 20 20">
                    <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.181 3.636a1 1 0 00.95.69h3.829c.969 0 1.371 1.24.588 1.81l-3.095 2.25a1 1 0 00-.364 1.118l1.181 3.636c.3.921-.755 1.688-1.54 1.118l-3.095-2.25a1 1 0 00-1.176 0l-3.095 2.25c-.785.57-1.84-.197-1.54-1.118l1.181-3.636a1 1 0 00-.364-1.118l-3.095-2.25c-.783-.57-.38-1.81.588-1.81h3.829a1 1 0 00.95-.69l1.181-3.636z" />
                </svg>
            </div>
            <span class="font-bold">4.9 rating</span>
        </div>

        <div class="flex items-center space-x-2 text-gray-600">
            <span class="text-gray-600"></span>
            <span>
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M15 19.128a9.38 9.38 0 0 0 2.625.372 9.337 9.337 0 0 0 4.121-.952 4.125 4.125 0 0 0-7.533-2.493M15 19.128v-.003c0-1.113-.285-2.16-.786-3.07M15 19.128v.106A12.318 12.318 0 0 1 8.624 21c-2.331 0-4.512-.645-6.374-1.766l-.001-.109a6.375 6.375 0 0 1 11.964-3.07M12 6.375a3.375 3.375 0 1 1-6.75 0 3.375 3.375 0 0 1 6.75 0Zm8.25 2.25a2.625 2.625 0 1 1-5.25 0 2.625 2.625 0 0 1 5.25 0Z" />
                </svg>
            </span>
            <span class="font-bold">20k+ growth community</span>
        </div>
    </div>
</section>
</template>

<script lang="ts">
import {
    defineComponent
} from 'vue';

export default defineComponent({
    name: 'TrustedBySection',
});
</script>

<style scoped>
section {
    padding-top: 2rem;
    padding-bottom: 2rem;
}

h2 {
    font-size: 0.875rem;
    font-weight: 700;
    text-transform: uppercase;
    color: #000;
    letter-spacing: 0.1em;
    margin-bottom: 1rem;
}

.flex {
    display: flex;
    justify-content: center;
    align-items: center;
}

.text-gray-600 {
    color: #6b7280;
    font-size: 0.875rem;
}

.text-gray-500 {
    color: #6b7280;
}

.text-gray-300 {
    color: #d1d5db;
}

.font-bold {
    font-weight: 700;
}
</style>
