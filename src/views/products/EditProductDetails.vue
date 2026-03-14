<script setup lang="ts">
import { FontAwesomeIcon } from "@fortawesome/vue-fontawesome";
import Column from "../../components/column/Column.vue";
import Header from "../../components/Header.vue";
import PageNavigation from "../../components/PageNavigation.vue";
import BasicInformationContents from "./BasicInformationContents.vue";
import TagsAndAttributeContents from "./TagsAndAttributeContents.vue";
import OrderSpesificationContents from "./OrderSpesificationContents.vue";
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
                <!-- <svg class="w-5 h-5" fill="currentColor" viewbox="0 0 20 20">
                  <path
                    d="M10 2a8 8 0 100 16 8 8 0 000-16zm1 11H9v-2h2v2zm0-4H9V5h2v4z"
                  ></path>
                </svg> -->
                <FontAwesomeIcon icon="fa-solid fa-circle-info" size="lg" />
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
               <FontAwesomeIcon icon="fa-solid fa-tag" size="lg" />
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
        <column>
          <template #title-name>
            <div class="flex items-center gap-3 mb-8">
              <div
                class="w-8 h-8 bg-blue-100 text-blue-900 rounded-lg flex items-center justify-center"
              >
                <FontAwesomeIcon icon="fa-solid fa-box-open" size="lg" />
              </div>
              <h3 class="text-xl font-bold text-slate-900">
                Order Spesifications
              </h3>
            </div>
          </template>
          <template #main-contents>
            <OrderSpesificationContents />
          </template>
        </column>
      </div>
      <!-- Left Column End -->
    </div>
  </main>
</template>
