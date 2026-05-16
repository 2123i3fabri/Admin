<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header class="bg-white shadow">
    <nav class="mx-auto flex max-w-4xl items-center gap-6 px-4 py-4">
      <h1 class="text-xl font-bold text-gray-900">Admin</h1>
      <RouterLink to="/" class="text-gray-600 hover:text-gray-900">Home</RouterLink>
      <RouterLink to="/about" class="text-gray-600 hover:text-gray-900">About</RouterLink>
    </nav>
  </header>
  <main class="mx-auto max-w-4xl px-4 py-8">
    <RouterView />
  </main>
</template>
