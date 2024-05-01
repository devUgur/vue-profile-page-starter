<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import TopnavComponent from './components/atoms/nav/TopnavComponent.vue'
import MenuButton from './components/atoms/nav/AMenuButton.vue'
import ABaseFooterSection from './components/atoms/sections/ABaseFooterSection.vue'
</script>

<template>
  <TopnavComponent />
  <RouterView />
  <div class="md:hidden lg:hidden">
    <MenuButton />
  </div>
  <ABaseFooterSection />
</template>

<style scoped></style>
