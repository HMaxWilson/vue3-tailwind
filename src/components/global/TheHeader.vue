<template>
  <header class="text-black">
    <div class="container mx-auto py-4 px-4">
      <div class="w-full flex col-span-1 sm:col-span-2 lg:col-span-2 justify-between">
        <RouterLink to="/">
          <h2 class="block text-2xl font-medium my-auto">HMaxWilson</h2>
        </RouterLink>
        <nav class="my-auto">
          <ul class="flex flex-wrap justify-center sm:justify-end text-sm font-medium leading-5">
            <li class="px-3 py-1 hover:font-bold"><RouterLink to="/">Home</RouterLink></li>
            <li class="px-3 py-1 hover:font-bold"><RouterLink to="/about">About</RouterLink></li>
          </ul>
        </nav>
      </div>
    </div>
  </header>
</template>

<script setup>
import { RouterLink } from 'vue-router'
</script>