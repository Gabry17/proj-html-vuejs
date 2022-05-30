<template>
  <div id="app">
    <!-- header -->
    <AppHeader />
    <!-- /header -->

    <!-- main -->
    <AppMainTop />
    <AppMainCenter />
    <!-- /main -->
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue';
import AppMainTop from './components/AppMainTop.vue';
import AppMainCenter from './components/AppMainCenter.vue';

export default {
  name: 'App',
  components: {
    AppHeader,
    AppMainTop,
    AppMainCenter
  }
}
</script>

<style lang="scss">
@import "./style/common";
@import "~@fortawesome/fontawesome-free/css/all.min.css";
</style>
