<script >
  import HeaderComp from './components/HeaderComp.vue';
  import MainComp from './components/MainComp.vue'
  import IconComp from './components/IconComp.vue'

  export default{
    components:{
      HeaderComp,
      MainComp,
      IconComp,
    }
  }
</script>

<template>
  <HeaderComp/> 
  <main>
    <MainComp/>
    <IconComp/>
  </main>
</template>

<style lang="scss">
@use './style/main.scss';
</style>
