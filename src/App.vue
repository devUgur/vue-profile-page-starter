<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import TopnavComponent from './components/TopnavComponent.vue'
import FooterComponent from './components/FooterComponent.vue'
import MenuButton from './components/nav/MenuButton.vue';
</script>

<template>
  <TopnavComponent></TopnavComponent>
  <RouterView />
  <FooterComponent></FooterComponent>
  <div class="md:hidden lg:hidden">

    <MenuButton />
  </div>
</template>

<style scoped></style>
