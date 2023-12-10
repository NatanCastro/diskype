<script setup lang="ts">
import Sidebar from '@/components/Sidebar.vue'
</script>

<template>
  <main>
    <Sidebar />
  </main>
</template>
<style scoped>
main {
  height: 100vh;
  display: grid;
  grid-template-columns: 2fr 10fr;
  background-color: #0f0f0ffe;
}
</style>
