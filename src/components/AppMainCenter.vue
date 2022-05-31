<template>
  <div class="main-center">
    <!-- top -->
    <AppCenterTop />
    <!-- /top -->
    <!-- center -->
    <AppCenter />
    <!-- /center -->
    <!-- bottom -->
    <!-- /bottom -->
  </div>
</template>

<script>
import AppCenterTop from './AppCenterTop';
import AppCenter from './AppCenter';

export default {
  name: "AppMainCenter",
  components: {
      AppCenterTop,
      AppCenter
  }
};
</script>

<style lang="scss" scoped>
@import '../style/variable';

.main-center{
    background-color: $hint-of-red-color;
}
</style>
