<script setup lang="ts">
import BaseSection from '@/components/sections/BaseSection.vue'
import ABaseImgModal from './animated/modals/ABaseImgModal.vue';

const props = defineProps(['button, position'])
const weAreSection = {
  title: 'We are awesome TEAM',
  content: [
    'Sed ut perspiciaatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium,',
  ],
  button: 'Info'
}
</script>

<template>
    <div>
        <ABaseImgModal />
        <BaseSection :button="props.button" :position="props.position"  :sectionItem="weAreSection" />
    </div>

</template>

<style scoped>
</style>
