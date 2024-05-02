<script setup lang="ts">
import { RouterView } from 'vue-router'
import TopnavComponent from './components/atoms/nav/TopnavComponent.vue'
import MenuButton from './components/atoms/nav/AMenuButton.vue'
import ABaseFooterSection from './components/atoms/sections/ABaseFooterSection.vue'
</script>

<template>
  <TopnavComponent  />
  <RouterView class="font-libre h-screen" />
  <ABaseFooterSection class="font-libre"  />
  <div class="lg:hidden font-libre">
    <MenuButton />
  </div>
</template>

<style scoped></style>
