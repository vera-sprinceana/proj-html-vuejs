<template>
  <div>
    <HeroComp/>
    <Sezione1Comp/>
  </div>
</template>

<script>
import HeroComp from './HeroComp.vue'
import Sezione1Comp from './Sezione1Comp.vue'
  export default {
    name: 'MainComp',
    components: {
      HeroComp,
      Sezione1Comp
    }
  }
</script>

<style scoped lang="scss">
  

  .bg-dark {
    background-color: rgba(6, 6, 7, 255);
  }

  
  
</style>