<template>
  <div class="main-center">
    <!-- top -->
    <AppCenterTop />
    <!-- /top -->
    <!-- center -->
    <!-- /center -->
    <!-- bottom -->
    <!-- /bottom -->
  </div>
</template>

<script>
import AppCenterTop from './AppCenterTop';

export default {
  name: "AppMainCenter",
  components: {
      AppCenterTop
  }
};
</script>

<style lang="scss" scoped>
@import '../style/variable';

.main-center{
    background-color: $hint-of-red-color;
}
</style>
