<template>
  <div role="status" class="space-y-3.5 animate-pulse w-100">
    <div class="flex items-center w-full space-x-2">
      <div class="h-3.5 bg-gray-200 rounded-full dark:bg-gray-700 w-32"></div>
      <div class="h-3.5 bg-gray-300 rounded-full dark:bg-gray-600 w-24"></div>
      <div class="h-3.5 bg-gray-300 rounded-full dark:bg-gray-600 w-full"></div>
    </div>
    <div class="flex items-center w-full space-x-2">
      <div class="h-3.5 bg-gray-200 rounded-full dark:bg-gray-700 w-full"></div>
      <div class="h-3.5 bg-gray-300 rounded-full dark:bg-gray-600 w-full"></div>
      <div class="h-3.5 bg-gray-300 rounded-full dark:bg-gray-600 w-24"></div>
    </div>
    <div class="flex items-center w-full space-x-2 max-w-[400px]">
      <div class="h-3.5 bg-gray-300 rounded-full dark:bg-gray-600 w-full"></div>
      <div class="h-3.5 bg-gray-200 rounded-full dark:bg-gray-700 w-80"></div>
      <div class="h-3.5 bg-gray-300 rounded-full dark:bg-gray-600 w-full"></div>
    </div>
    <div class="flex items-center w-full space-x-2">
      <div class="h-3.5 bg-gray-200 rounded-full dark:bg-gray-700 w-full"></div>
      <div class="h-3.5 bg-gray-300 rounded-full dark:bg-gray-600 w-full"></div>
      <div class="h-3.5 bg-gray-300 rounded-full dark:bg-gray-600 w-24"></div>
    </div>
    <div class="flex items-center w-full space-x-2">
      <div class="h-3.5 bg-gray-300 rounded-full dark:bg-gray-600 w-32"></div>
      <div class="h-3.5 bg-gray-300 rounded-full dark:bg-gray-600 w-24"></div>
      <div class="h-3.5 bg-gray-200 rounded-full dark:bg-gray-700 w-full"></div>
    </div>
    <div class="flex items-center w-full space-x-2">
      <div class="h-3.5 bg-gray-300 rounded-full dark:bg-gray-600 w-full"></div>
      <div class="h-3.5 bg-gray-200 rounded-full dark:bg-gray-700 w-80"></div>
      <div class="h-3.5 bg-gray-300 rounded-full dark:bg-gray-600 w-full"></div>
    </div>
    <span class="sr-only">Loading...</span>
  </div>
</template>

<script lang="ts">
import { Options, Vue, prop } from "vue-class-component";

class Props {}

@Options({
  components: {},
})
export default class MainSkeleton extends Vue.with(Props) {}
</script>
