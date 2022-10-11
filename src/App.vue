<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import InfiniteScroll from "./components/InfiniteScroll.vue";
</script>

<template>
  <main>
    <h1>Infinite Scrolling Component</h1>
    <Suspense>
      <InfiniteScroll />
      <template #fallback>
        <p>Loading...</p>
      </template>
    </Suspense>
    <p>Made with ❤️ By Parkpoom Pongsawat</p>
  </main>
</template>
