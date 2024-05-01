<template>
  <div class="grid place-content-center border bg-gray-800 text-white p-9 font-bold text-2xl" id="about-view">
    <h1>{{ props.content }}</h1>
  </div>
</template>

<script setup lang="ts">
const props = defineProps(['content'])
</script>

<style scoped>

</style>