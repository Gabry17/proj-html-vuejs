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

    <!-- footer -->
    <AppFooter />
    <!-- /footer -->
  </div>
</template>

<script>
import AppHeader from "./components/AppHeader.vue";
import AppMainTop from "./components/AppMainTop.vue";
import AppMainCenter from "./components/AppMainCenter.vue";
import AppMainBottom from "./components/AppMainBottom.vue";
import AppFooter from "./components/AppFooter.vue";

export default {
  name: "App",
  components: {
    AppHeader,
    AppMainTop,
    AppMainCenter,
    AppMainBottom,
    AppFooter,
  }
};
</script>

<style lang="scss">
@import "./style/common";
@import "~@fortawesome/fontawesome-free/css/all.min.css";
</style>
