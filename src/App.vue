<template>
  <div id="app">
    <!-- header -->
    <AppHeader />
    <!-- /header -->
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue';

export default {
  name: 'App',
  components: {
    AppHeader
  }
}
</script>

<style lang="scss">
@import "./style/common";
@import "~@fortawesome/fontawesome-free/css/all.min.css";
</style>
