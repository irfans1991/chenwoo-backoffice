<template>
  <div class="space-y-6">
    <div>
      <label class="block text-sm font-semibold text-slate-700 mb-2"
        >Product Name</label
      >
      <input
        class="w-full px-4 py-3 rounded-xl border-slate-200 focus:ring-blue-500 focus:border-blue-500 bg-primary-input"
        type="text"
        value="Bluefin Tuna Saku AAA"
      />
    </div>
    <div class="grid grid-cols-2 gap-6">
      <div>
        <label class="block text-sm font-semibold text-slate-700 mb-2"
          >Category</label
        >
        <select
          class="w-full px-4 py-3 rounded-xl border-slate-200 focus:ring-blue-500 focus:border-blue-500 bg-primary-input appearance-none"
        >
          <option>Saku Blocks</option>
          <option>Whole Fish</option>
          <option>Steaks</option>
        </select>
      </div>
      <div>
        <label class="block text-sm font-semibold text-slate-700 mb-2"
          >Production Status</label
        >
        <select
          class="w-full px-4 py-3 rounded-xl border-slate-200 focus:ring-blue-500 focus:border-blue-500 bg-primary-input appearance-none"
        >
          <option>In Production</option>
          <option>Out of Stock</option>
          <option>Discontinued</option>
        </select>
      </div>
    </div>
    <div>
      <label class="block text-sm font-semibold text-slate-700 mb-2"
        >Description &amp; Grading Standards</label
      >
      <textarea
        class="w-full px-4 py-3 rounded-xl border-slate-200 focus:ring-blue-500 focus:border-blue-500 bg-primary-input custom-scrollbar"
        rows="5"
      >
Our AAA grade Bluefin Tuna Saku is hand-selected for deep red color and firm texture. Perfect for high-end sushi and sashimi applications. Vacuum sealed for maximum freshness.</textarea
      >
    </div>
  </div>
</template>
