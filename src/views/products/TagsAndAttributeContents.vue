<template>
  <!-- <div class="grid grid-cols-2 gap-8">
    <div>
      <label class="block text-sm font-semibold text-slate-700 mb-4"
        >Sustainability Labels</label
      >
      <div class="space-y-3">
        <label
          class="flex items-center p-3 border-2 border-blue-900 bg-blue-50/50 rounded-xl cursor-pointer group"
        >
          <input
            checked=""
            class="w-5 h-5 text-blue-900 border-slate-300 rounded focus:ring-blue-500"
            type="checkbox"
          />
          <span class="ml-3 text-sm font-bold text-blue-900"
            >MSC Applicable</span
          >
          <svg
            class="w-4 h-4 ml-auto text-blue-900"
            fill="currentColor"
            viewbox="0 0 20 20"
          >
            <path
              clip-rule="evenodd"
              d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
              fill-rule="evenodd"
            ></path>
          </svg>
        </label>
        <label
          class="flex items-center p-3 border border-slate-200 rounded-xl cursor-pointer hover:bg-slate-50"
        >
          <input
            class="w-5 h-5 text-blue-900 border-slate-300 rounded focus:ring-blue-500"
            type="checkbox"
          />
          <span class="ml-3 text-sm font-medium text-slate-600"
            >FIP Applicable</span
          >
        </label>
      </div>
    </div>
    <div>
      <label class="block text-sm font-semibold text-slate-700 mb-4"
        >Species Classification</label
      >
      <input
        class="w-full px-4 py-3 rounded-xl border-slate-200 focus:ring-blue-500 focus:border-blue-500 bg-slate-50/50"
        type="text"
        value="Thunnus albacares (Yellowfin Tuna)"
      />
      <p class="text-[10px] text-slate-400 mt-2 italic">
        Scientific name and common name for traceability.
      </p>
    </div>
  </div> -->

  <div class="grid grid-cols-2 gap-8">
  <div>
    <label class="block text-sm font-semibold text-slate-700 mb-4">
      Sustainability Labels
    </label>

    <div class="space-y-3">
      <!-- MSC -->
      <label
        for="msc"
        class="flex items-center p-3 border-2 border-blue-900 bg-blue-50/50 rounded-xl cursor-pointer group"
      >
        <input
          id="msc"
          name="sustainability"
          type="checkbox"
          checked
          class="w-5 h-5 text-blue-900 border-slate-300 rounded focus:ring-blue-500"
        />

        <span class="ml-3 text-sm font-bold text-blue-900">
          MSC Applicable
        </span>

        <svg
          class="w-4 h-4 ml-auto text-blue-900"
          fill="currentColor"
          viewBox="0 0 20 20"
        >
          <path
            fill-rule="evenodd"
            clip-rule="evenodd"
            d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 
            1 0 00-1.414-1.414L9 10.586 
            7.707 9.293a1 1 0 00-1.414 
            1.414l2 2a1 1 0 001.414 
            0l4-4z"
          ></path>
        </svg>
      </label>

      <!-- FIP -->
      <label
        for="fip"
        class="flex items-center p-3 border border-slate-200 rounded-xl cursor-pointer hover:bg-slate-50"
      >
        <input
          id="fip"
          name="sustainability"
          type="checkbox"
          class="w-5 h-5 text-blue-900 border-slate-300 rounded focus:ring-blue-500"
        />

        <span class="ml-3 text-sm font-medium text-slate-600">
          FIP Applicable
        </span>
      </label>
    </div>
  </div>

  <div>
    <label class="block text-sm font-semibold text-slate-700 mb-4">
      Species Classification
    </label>

    <input
      type="text"
      value="Thunnus albacares (Yellowfin Tuna)"
      class="w-full px-4 py-3 rounded-xl border border-slate-200 focus:ring-blue-500 focus:border-blue-500 bg-slate-50/50"
    />

    <p class="text-[10px] text-slate-400 mt-2 italic">
      Scientific name and common name for traceability.
    </p>
  </div>
</div>
</template>
