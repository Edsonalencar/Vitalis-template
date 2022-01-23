<script setup lang="ts">
  import HelloWorld from '../components/HelloWorld.vue'
  import { ref } from 'vue'

  const count = ref(0)
</script>

<template>
  <div class="min-h-full flex flex-col items-center justify-center">
    <img alt="Vue logo" src="../assets/logo.png" class="mt-10" />
    <button
      @click="count++"
      class="py-1 px-3 border text-sm font-medium rounded-md text-black"
    >
      Count: {{ count }}
    </button>
    <HelloWorld msg="Vite + Vue 3 + Typescript + Tailwind 3 + Vue Rounter 4" />
    <div class="inline-flex rounded-md shadow mt-10">
      <router-link
        to="/about"
        class="inline-flex items-center justify-center px-4 py-2 text-base font-medium leading-6 text-white transition duration-150 ease-in-out bg-indigo-600 border border-transparent rounded-md hover:bg-indigo-500 focus:outline-none"
        >Next Page</router-link
      >
    </div>
  </div>
</template>
