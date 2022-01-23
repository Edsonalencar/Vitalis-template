<script setup lang="ts">
  defineProps<{ msg: string }>()
</script>

<template>
  <h1
    class="text-3xl font-extrabold leading-9 tracking-tight text-gray-900 sm:text-4xl sm:leading-10 my-7"
  >
    {{ msg }}
  </h1>
  <div class="flex flex-row mt-2">
    <a
      class="text-indigo-600"
      href="https://v3.vuejs.org/guide/introduction.html"
      target="_blank"
    >
      Vue 3
    </a>
    <div class="mx-2">|</div>
    <a
      class="text-indigo-600"
      href="https://tailwindcss.com/docs/installation"
      target="_blank"
    >
      Tailwind
    </a>
  </div>
</template>
