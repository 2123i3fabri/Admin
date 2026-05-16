<script setup lang="ts">
import { ref } from "vue";

const count = ref(0);
</script>

<template>
  <div class="flex flex-col items-center gap-4">
    <h2 class="text-2xl font-semibold text-gray-800">Home</h2>
    <p class="text-gray-600">Welcome to the Admin application.</p>
    <button
      class="rounded bg-indigo-600 px-4 py-2 text-white hover:bg-indigo-700"
      @click="count++"
    >
      Count: {{ count }}
    </button>
  </div>
</template>
