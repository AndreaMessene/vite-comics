<script >
  import HeaderComp from './components/HeaderComp.vue';
  import MainComp from './components/MainComp.vue'
  import IconComp from './components/IconComp.vue'
  import FooterComp from './components/FooterComp.vue'

  export default{
    components:{
      HeaderComp,
      MainComp,
      IconComp,
      FooterComp,
    }
  }
</script>

<template>
  <HeaderComp/> 
  <main>
    <MainComp/>
    <IconComp/>
  </main>
  <FooterComp/>
</template>

<style lang="scss">
@use './style/main.scss';
</style>
