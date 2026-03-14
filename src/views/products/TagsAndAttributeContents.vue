<script setup lang="ts">
import { FontAwesomeIcon } from "@fortawesome/vue-fontawesome";
</script>

<template>
  <div class="grid grid-cols-2 gap-8">
    <div>
      <label class="block text-md font-semibold text-slate-700 mb-4">
        Sustainability Labels
      </label>

      <div class="space-y-3">
        <!-- MSC -->
        <label
          for="msc"
          class="flex items-center gap-3 px-3 py-2 border-2 border-blue-900 bg-blue-50/50 rounded-xl cursor-pointer w-fit"
        >
          <input id="msc" type="checkbox" class="peer hidden" checked />

          <span
            class="flex items-center justify-center w-5 h-5 border-2 border-blue-900 rounded-full peer-checked:bg-blue-900"
          >
            <FontAwesomeIcon
              icon="fa-solid fa-check"
              class="text-white text-xs hidden peer-checked:block"
            />
          </span>

          <span class="text-sm font-bold text-blue-900"> MSC Applicable </span>
        </label>

        <!-- FIP -->
        <label
          for="fip"
          class="flex items-center  gap-3 px-3 py-2 border-2 border-blue-900 bg-blue-50/50 rounded-xl cursor-pointer w-fit"
        >
           <input id="fip" type="checkbox" class="peer hidden" />

          <span
            class="flex items-center justify-center w-5 h-5 border-2 border-blue-900 rounded-full peer-checked:bg-blue-900"
          >
            <FontAwesomeIcon
              icon="fa-solid fa-check"
              class="text-white text-xs hidden peer-checked:block"
            />
          </span>

          <span class="ml-3 text-sm font-medium text-slate-600">
            FIP Applicable
          </span>
        </label>
      </div>
    </div>

    <div>
      <label class="block text-md font-semibold text-slate-700 mb-4">
        Species Classification
      </label>

      <input
        type="text"
        value="Thunnus albacares (Yellowfin Tuna)"
        class="w-full px-4 py-3 rounded-xl border border-slate-200 focus:ring-blue-500 focus:border-blue-500 bg-primary-input"
      />

      <p class="text-[10px] text-slate-400 mt-2 italic">
        Scientific name and common name for traceability.
      </p>
    </div>
  </div>
</template>
