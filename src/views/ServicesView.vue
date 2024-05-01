<script setup lang="ts">
import LinearProgressBar from "@/components/animated/bars/LinearProgressBar.vue"
import ABaseImageSection from "@/components/ABaseImageSection.vue";
import ABaseImgModal from "@/components/animated/modals/ABaseImgModal.vue"
import ABaseIntroSection from "@/components/ABaseIntroSection.vue"
import ABaseIconSection from "@/components/ABaseIconSection.vue";
const weAreSection = {
  title: 'We are awesome TEAM',
  content: [
    'Sed ut perspiciaatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas',
  ],
  button: 'Info'
}
</script>

<template>
  <ABaseIntroSection :content="'Home | Services'" />
  <div class="flex gap-7">
    <ABaseImageSection :button="false" :position="'left'"  :sectionItem="weAreSection" />
    <ABaseImageSection :button="false" :position="'left'"  :sectionItem="weAreSection" />
    <ABaseImageSection :button="false" :position="'left'"  :sectionItem="weAreSection" />

    <hr />
  </div>
  <div class="grid grid-cols-3 gap-6 place-content-center">
    <ABaseIconSection  :button="false" :position="'left'"  :sectionItem="weAreSection"  />
    <ABaseIconSection  :button="false" :position="'left'"  :sectionItem="weAreSection"  />
    <ABaseIconSection  :button="false" :position="'left'"  :sectionItem="weAreSection"  />
    <ABaseIconSection  :button="false" :position="'left'"  :sectionItem="weAreSection"  />
    <ABaseIconSection  :button="false" :position="'left'"  :sectionItem="weAreSection"  />
    <ABaseIconSection  :button="false" :position="'left'"  :sectionItem="weAreSection"  />
  </div>

</template>

<style scoped>
</style>
