<script setup lang="ts">
defineProps({
    name: String
})
</script>

<template>
  <button
    class="bg-blue-900 text-white px-4 py-2.5 rounded-2xl font-semibold hover:bg-blue-800 transition-all text-sm">
    {{ name }}
  </button>
</template>
