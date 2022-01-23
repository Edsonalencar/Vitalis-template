<template>
<div class="mt-10">
  <div
    class="min-h-full mt-10 flex flex-col items-center justify-center px-4 py-12 sm:px-6 lg:py-16 lg:px-8"
  >
    <h2
      class="text-3xl text-center font-extrabold leading-9 tracking-tight text-gray-900 sm:text-4xl sm:leading-10"
    >
      About Page
      <div class="my-3"></div>
      <span class="text-indigo-600"
        >Vite + Vue 3 + Typescript + Tailwind 3 + Vue Rounter 4</span
      >
    </h2>
    <div class="flex mt-8 lg:flex-shrink-0 lg:mt-12">
      <div class="inline-flex rounded-md shadow">
        <router-link
          to="/"
          class="inline-flex items-center justify-center px-5 py-3 text-base font-medium leading-6 text-white transition duration-150 ease-in-out bg-indigo-600 border border-transparent rounded-md hover:bg-indigo-500 focus:outline-none"
          >Back Home</router-link
        >
      </div>
    </div>
  </div>
</div>
</template>
