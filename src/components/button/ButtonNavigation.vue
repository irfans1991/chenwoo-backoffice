<script setup lang="ts">
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome';

defineProps<{
  name: string;
}>();
</script>

<template>
  <a
    class="inline-flex items-center text-xs font-bold text-blue-900 uppercase tracking-widest hover:text-blue-950 mb-4"
    href="#"
  >

  <FontAwesomeIcon icon="fa-solid fa-chevron-left" size="lg"/>
    {{ name }}
  </a>
</template>
