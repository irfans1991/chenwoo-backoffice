<script setup lang="ts">
import Column from "../../components/column/Column.vue";
import Header from "../../components/Header.vue";
import LeftColumn from "../../components/LeftColumn.vue";
import MainContents from "../../components/MainContents.vue";
import PageNavigation from "../../components/PageNavigation.vue";
import BasicInformationContents from "./BasicInformationContents.vue";
import TagsAndAttributeContents from "./TagsAndAttributeContents.vue";
</script>

<template>
  <Header />
  <main class="max-w-[1440px] mx-auto px-6 py-8">
    <PageNavigation />
    <div class="grid grid-cols-12 gap-8 items-start">
      <!-- Left Column Start -->
      <div class="col-span-8 space-y-8">
        <Column>
          <template #title-name>
            <div class="flex items-center gap-3 mb-8">
              <div
                class="w-8 h-8 bg-blue-100 text-blue-900 rounded-lg flex items-center justify-center"
              >
                <svg class="w-5 h-5" fill="currentColor" viewbox="0 0 20 20">
                  <path
                    d="M10 2a8 8 0 100 16 8 8 0 000-16zm1 11H9v-2h2v2zm0-4H9V5h2v4z"
                  ></path>
                </svg>
              </div>
              <h3 class="text-xl font-bold text-slate-900">
                Basic Information
              </h3>
            </div>
          </template>
          <template #main-contents>
            <BasicInformationContents />
          </template>
        </Column>
        <Column>
          <template #title-name>
            <div class="flex items-center gap-3 mb-8">
              <div
                class="w-8 h-8 bg-blue-100 text-blue-900 rounded-lg flex items-center justify-center"
              >
                <svg class="w-5 h-5" fill="currentColor" viewbox="0 0 24 24">
                  <path
                    d="M17.41 7.58l-5-5C12.05 2.22 11.55 2 11 2H6c-1.1 0-2 .9-2 2v5c0 .55.22 1.05.59 1.42l5 5c.36.37.86.58 1.41.58s1.05-.21 1.41-.58l5-5c.37-.36.59-.86.59-1.42 0-.57-.23-1.06-.59-1.42zM6.5 7C5.67 7 5 6.33 5 5.5S5.67 4 6.5 4 8 4.67 8 5.5 7.33 7 6.5 7z"
                  ></path>
                  />
                </svg>
              </div>
              <h3 class="text-xl font-bold text-slate-900">
                Tags &amp; Attributes
              </h3>
            </div>
          </template>
          <template #main-contents>
            <TagsAndAttributeContents />
          </template>
        </Column>
      </div>
      <!-- Left Column End -->
    </div>
  </main>
</template>
