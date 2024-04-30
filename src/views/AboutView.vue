<script setup lang="ts">
import LinearProgressBar from "@/components/animated/bars/LinearProgressBar.vue"
import BaseSection from '@/components/sections/BaseSection.vue'
import ABaseImgModal from "@/components/animated/modals/ABaseImgModal.vue"
const weAreSection = {
  title: 'We are awesome TEAM',
  content: [
    'Sed ut perspiciaatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas',
    'Sed ut perspiciaatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas'
  ],
  button: 'Info'
}
const chooseSection = {
  title: 'Why Choose Us?',
  content: [
    'Sed ut perspiciaatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur. ',
    'Sed ut perspiciaatis iste natus error sit voluptatem probably havent heard of them accusamus.',
  ],
  button: ''
}
</script>

<template>
  <div class="grid place-content-center border bg-slate-500 text-white p-9 font-bold text-2xl" id="about-view">
    <h1>Home | About Us</h1>
  </div>
  <div class="grid place-content-center w-50 mx-auto ">

    <BaseSection :button="true" :position="'center'"  :sectionItem="weAreSection" />
    <hr />
    <div class="md:flex flex-row">
      <BaseSection :button="false" :position="'right'" :sectionItem="chooseSection" />
      <div class="my-auto">
        <LinearProgressBar />
        <LinearProgressBar />
        <LinearProgressBar />
      </div>
        <ABaseImgModal />
    </div>
  </div>

</template>

<style scoped>
</style>
