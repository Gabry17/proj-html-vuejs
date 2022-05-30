<template>
  <div class="main-top">
    <div class="text">
      <h2>ciao sono un h2</h2>
      <p>ciao coa cao</p>
      <p>ciao</p>
    </div>
    <div class="flex">
      <div class="info">
        <div>1926</div>
        <p>finished sessions</p>
      </div>
      <div class="info">
        <div>1926</div>
        <p>finished sessions</p>
      </div>
      <div class="info">
        <div>1926</div>
        <p>finished sessions</p>
      </div>
      <div class="info">
        <div>1926</div>
        <p>finished sessions</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppMainTop",
};
</script>

<style lang="scss" scoped>
@import "../style/variable";
.main-top {
  width: $project-width;
  margin: $project-margin;
  .text {
    padding: 3em;
    text-align: center;
    h2 {
      margin-bottom: 1em;
    }
  }

  .flex {
    display: flex;
    text-align: center;
    .info {
      width: calc(100% / 4);
    }
  }
}
</style>
