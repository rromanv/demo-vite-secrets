<script setup>
import { ref } from 'vue'
const title = ref(import.meta.env.VITE_APP_NAME)
const message = ref(import.meta.env.VITE_MESSAGE)
</script>

<template>
  <main
    class="flex flex-col justify-center items-center min-h-screen bg-gray-900 gap-16"
  >
    <h1 class="text-8xl font-light text-gray-400">{{ title }}!</h1>
    <p class="text-3xl font-serif text-yellow-600">{{ message }}!</p>
  </main>
</template>
