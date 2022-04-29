<template>
  <div>
    <HeroComp/>
    <Sezione1Comp/>
    <SectionVideo/>
    <VideoComp/>
    <SectionTwo/>
    <CardsComp/>
    <SectionArticles/>
    <MegaSection/>
  </div>
</template>

<script>
import HeroComp from './HeroComp.vue'
import Sezione1Comp from './Sezione1Comp.vue'
import SectionVideo from './SectionVideo.vue'
import VideoComp from './VideoComp.vue'
import SectionTwo from './SectionTwo.vue'
import CardsComp from './CardsComp.vue'
import SectionArticles from './SectionArticles.vue'
import MegaSection from './MegaSection.vue'

  export default {
    name: 'MainComp',
    components: {
      HeroComp,
      Sezione1Comp,
      SectionVideo,
      VideoComp,
      SectionTwo,
      CardsComp,
      SectionArticles,
      MegaSection
    }
  }
</script>

<style scoped lang="scss">
  

  .bg-dark {
    background-color: rgba(6, 6, 7, 255);
  }

  
  
</style>