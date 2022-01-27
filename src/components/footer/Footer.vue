<template>
    
    <footer>
        <FooterTop />
        <FooterMiddle />
        <FooterBottom />
    </footer>

</template>

<script>
    import FooterTop from '../FooterTop.vue';
    import FooterMiddle from '../FooterMiddle.vue';
    import FooterBottom from '../FooterBottom.vue';

    export default {
        name: 'Footer',
    }
</script>

<style lang="scss" scoped>

  @import "../../assets/style/partials/variables.scss";
  header {
    background-color: white;
  }
</style>