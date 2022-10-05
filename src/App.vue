<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header>
    <div class="max-w-7xl mx-auto">
      <nav class="p-2">
        <RouterLink
          class="
            px-4
            py-2
            mr-4
            bg-indigo-600
            hover:bg-indigo-800
            rounded
            text-white
          "
          to="/"
          >Home</RouterLink
        >
        <RouterLink
          to="/skills"
          class="
            px-4
            py-2
            mr-4
            bg-indigo-600
            hover:bg-indigo-800
            rounded
            text-white
          "
          >Skills</RouterLink
        >
      </nav>
    </div>
  </header>

  <main class="max-w-7xl mx-auto min-h-screen">
    <RouterView />
  </main>
</template>
