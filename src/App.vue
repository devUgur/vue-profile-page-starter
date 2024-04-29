<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import TopnavComponent from './components/TopnavComponent.vue'
import FooterComponent from './components/FooterComponent.vue'
</script>

<template>
  <TopnavComponent></TopnavComponent>
  <RouterView />
  <FooterComponent></FooterComponent>
</template>

<style scoped></style>
