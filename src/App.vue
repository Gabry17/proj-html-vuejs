<template>
  <div id="app">
    <!-- header -->
    <AppHeader />
    <!-- /header -->
    
    <!-- main -->
    <AppMainTop />
    <!-- /main -->
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue';
import AppMainTop from './components/AppMainTop.vue';

export default {
  name: 'App',
  components: {
    AppHeader,
    AppMainTop
  }
}
</script>

<style lang="scss">
@import "./style/common";
@import "~@fortawesome/fontawesome-free/css/all.min.css";
</style>
