<script setup lang="ts">
defineProps({
  name: String,
});
</script>

<template>
  <a
    class="inline-flex items-center text-xs font-bold text-blue-900 uppercase tracking-widest hover:text-blue-950 mb-4"
    href="#"
  >
    <svg
      class="w-6 h-6 mr-2"
      fill="none"
      stroke="currentColor"
      viewbox="0 0 24 24"
    >
      <path
        d="M15 19l-7-7 7-7"
        stroke-linecap="round"
        stroke-linejoin="round"
        stroke-width="2.5"
      ></path>
    </svg>
    {{ name }}
  </a>
</template>
