<script setup lang="ts">
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome';

</script>

<template>

    <div class="grid grid-cols-2 gap-4">
      <!-- Spec Item: Active -->
      <div
        class="p-4 border-2 border-blue-900 bg-blue-50/30 rounded-2xl flex items-start gap-4 cursor-pointer"
      >
        <div
          class="w-5 h-5 mt-1 bg-blue-900 rounded-full flex items-center justify-center"
        >
         <FontAwesomeIcon icon="fa-solid fa-check-circle" size="lg" class="bg-blue-700" />
        </div>
        <div>
          <p class="font-bold text-slate-900 text-sm">2kg Vacuum Pack</p>
          <p class="text-xs text-slate-500">Standard retail/chef pack</p>
        </div>
      </div>
      <!-- Spec Item: Active -->
      <div
        class="p-4 border-2 border-blue-900 bg-blue-50/30 rounded-2xl flex items-start gap-4 cursor-pointer"
      >
        <div
          class="w-5 h-5 mt-1 bg-blue-900 rounded-full flex items-center justify-center"
        >
          <svg
            class="w-3 h-3 text-white"
            fill="currentColor"
            viewbox="0 0 20 20"
          >
            <path
              d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"
            ></path>
          </svg>
        </div>
        <div>
          <p class="font-bold text-slate-900 text-sm">10kg Master Carton</p>
          <p class="text-xs text-slate-500">Bulk logistics packaging</p>
        </div>
      </div>
      <!-- Spec Item: Inactive -->
      <div
        class="p-4 border border-slate-200 rounded-2xl flex items-start gap-4 cursor-pointer hover:bg-slate-50 transition-colors"
      >
        <div class="w-5 h-5 mt-1 border border-slate-300 rounded-full"></div>
        <div>
          <p class="font-bold text-slate-700 text-sm">
            5kg IWP (Individual Poly)
          </p>
          <p class="text-xs text-slate-500">Frozen single-wrap pieces</p>
        </div>
      </div>
      <!-- Add Button -->
      <button
        class="p-4 border border-slate-200 border-dashed rounded-2xl flex items-center justify-center gap-2 hover:bg-slate-50 hover:border-slate-400 transition-all text-slate-400 hover:text-slate-600"
      >
        <span class="text-lg font-bold">+</span>
        <span class="text-sm font-bold">Add New Spec</span>
      </button>
    </div>

</template>
