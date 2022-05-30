<template>
  <header>
    <div class="container">
      <div class="logo">logo</div>
      <div class="list-menu">menu menu menu menu</div>
    </div>
    <!-- banner -->
    <AppBanner />
    <!-- /banner -->
  </header>
</template>

<script>
import AppBanner from './AppBanner.vue';

export default {
  name: "AppHeader",
  components: {
    AppBanner
  }
};
</script>

<style lang="scss" scoped>
@import "../style/variable";
header {
  background-color: $port-gore-color;
  color: $white-color;
  .container {
    max-width: 1200px;
    display: flex;
    justify-content: space-between;
    line-height: 50px;
    width: $project-width;
    margin: $project-margin;
  }
}
</style>
