<template>
    <svg :class="`${className}`" data-slot="icon" fill="none" :stroke-width="`${stroke ?? '1.5'}`" stroke="currentColor"
        viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
        <path stroke-linecap="round" stroke-linejoin="round" d="M12 9v6m3-3H9m12 0a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z">
        </path>
    </svg>
</template>
<script setup lang="ts">
defineProps<{ className?: string, stroke?: string }>()
</script>