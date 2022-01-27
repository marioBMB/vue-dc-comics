<template>
    
    <header>
        <SiteLogo />
        <MainNav />
    </header>

</template>

<script>
  import SiteLogo from './components/Sitelogo.vue';
  import MainNav from './components/header/MainNav.vue';


  export default {
    name: 'Header',
  }
  
</script>

<style lang="scss" scoped>

  @import "../../assets/style/partials/variables.scss";
  header {
    background-color: white;
  }
</style>