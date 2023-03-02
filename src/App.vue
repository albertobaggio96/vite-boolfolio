<script>
  import MainApp from './components/MainApp.vue';

  export default{
    name:app,
    components:{
      MainApp,
    }
  }
</script>

<template>
  <MainApp/>
</template>

<style lang="scss">
  @use './styles/general.scss'as *;
  @use 'bootstrap/scss/bootstrap.scss' as *;

  
</style>
