<script setup>
import { ref } from "vue"

var props= defineProps(["class"])
const  classData = ref(props.class);
</script>
<template>
    <svg data-slot="icon" fill="none" class="h-5 w-5" stroke-width="1.5" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
  <path stroke-linecap="round" stroke-linejoin="round" d="m4.5 12.75 6 6 9-13.5"></path>
</svg>
</template>