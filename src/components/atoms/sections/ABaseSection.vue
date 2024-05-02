<template>
    <div class="">
        <div>

            <h1 class="font-bold text-2xl" :class="{ 'float-end': position === 'right', 'text-center': position === 'center' }">{{ sectionItem.title }}</h1> <!-- Adjusted class binding -->
        </div>
        <div class="user-box">
          <p v-for="content in sectionItem.content" class="text-slate-400" :key="content">
            {{ content }}
          </p>
        </div>
        <button v-if="button" href="#">
          {{ sectionItem.button }}
        </button>
    </div>
</template>

<script setup lang="ts">
interface Section {
  title: string
  content: string[]
  button: string
}
export interface BaseSection {
  button?: boolean
  position: string
  sectionItem: Section
}
defineProps<BaseSection>()
</script>

<style lang="scss" scoped>

</style>