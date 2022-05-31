<template>
  <div class="main-center">
    <!-- top -->
    <AppCenterTop />
    <!-- /top -->

    <!-- center -->
    <AppCenter />
    <!-- /center -->
    
    <!-- bottom -->
    <AppCenterBottom />
    <!-- /bottom -->
  </div>
</template>

<script>
import AppCenterTop from './AppCenterTop';
import AppCenter from './AppCenter';
import AppCenterBottom from './AppCenterBottom';

export default {
  name: "AppMainCenter",
  components: {
      AppCenterTop,
      AppCenter,
      AppCenterBottom
  }
};
</script>

<style lang="scss" scoped>
@import '../style/variable';

.main-center{
    background-color: $hint-of-red-color;
}
</style>
