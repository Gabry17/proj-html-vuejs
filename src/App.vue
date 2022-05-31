<template>
  <div id="app">
    <!-- header -->
    <AppHeader />
    <!-- /header -->

    <!-- main -->
    <AppMainTop />
    <AppMainCenter />
    <AppMainBottom />
    <!-- /main -->
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue';
import AppMainTop from './components/AppMainTop.vue';
import AppMainCenter from './components/AppMainCenter.vue';
import AppMainBottom from './components/AppMainBottom.vue';


export default {
  name: 'App',
  components: {
    AppHeader,
    AppMainTop,
    AppMainCenter,
    AppMainBottom
  }
}
</script>

<style lang="scss">
@import "./style/common";
@import "~@fortawesome/fontawesome-free/css/all.min.css";
</style>
