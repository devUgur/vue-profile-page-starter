<script setup lang="ts">
import LinearProgressBar from "@/components/atoms/bars/LinearProgressBar.vue"
import BaseSection from '@/components/atoms/sections/ABaseSection.vue'
import ABaseImgModal from "@/components/atoms/img/ABaseImgModal.vue"
import ABaseIntroSection from "@/components/atoms/sections/ABaseIntroSection.vue"
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
    <BaseSection class="w-[50%]" :button="true" :position="'center'"  :sectionItem="weAreSection" />
    <hr />
    <ABaseIntroSection  :content="'Home | About'" />
    <div class="md:flex flex-row my-10 gap-10 p-10">
      <div class=" w-[50%]">

        <BaseSection :button="false" :position="'right'" :sectionItem="chooseSection" />
      </div>
      <div class="my-auto">
        <LinearProgressBar />
        <LinearProgressBar />
        <LinearProgressBar />
      </div>
        <ABaseImgModal />
    </div>

</template>

<style scoped>
</style>
