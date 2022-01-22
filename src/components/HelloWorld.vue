<script setup lang="ts">
  import { ref } from 'vue'

  defineProps<{ msg: string }>()

  const count = ref(0)
</script>

<template>
    <button
      @click="count++"
      class="mt-4 py-1 px-3 border border-transparent text-sm font-medium rounded-md text-white bg-[#059669]"
    >
      Count: {{ count }}
    </button>
  <h1 class="text-3xl font-bold underline my-7">
    {{ msg }}
  </h1>
  <div class="flex flex-row">
    <a href="https://v3.vuejs.org/guide/introduction.html">Vue 3</a>
    <div class="mx-2">|</div>
    <a href="https://tailwindcss.com/docs/installation">Tailwind</a>
  </div>
</template>

<style scoped>
  a {
    color: #42b983;
  }

  label {
    margin: 0 0.5em;
    font-weight: bold;
  }

  code {
    background-color: #eee;
    padding: 2px 4px;
    border-radius: 4px;
    color: #304455;
  }
</style>
