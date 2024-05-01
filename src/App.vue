<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import TopnavComponent from './components/atoms/nav/TopnavComponent.vue'
import MenuButton from './components/atoms/nav/AMenuButton.vue'
import ABaseFooterSection from './components/atoms/sections/ABaseFooterSection.vue'
</script>

<template>
  <TopnavComponent class="font-libre"  />
  <RouterView class="font-libre" />
  <div class="md:hidden lg:hidden font-libre">
    <MenuButton />
  </div>
  <ABaseFooterSection class="font-libre"  />
</template>

<style scoped></style>
