<script setup>
import { RouterLink, RouterView } from 'vue-router'
import FloatingPrimaryLogoHolder from './components/FloatingPrimaryLogoHolder.vue'
</script>

<template>
  <header class="w-full bg-gray-50">
    <FloatingPrimaryLogoHolder></FloatingPrimaryLogoHolder>
  </header>
  <RouterView />
</template>
<style>
body {
  overflow-x: hidden;
}
</style>