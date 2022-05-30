<template>
  <div class="center-top">
    <div class="text">
      <p>choose a course to get started</p>
      <h2>Latest Featured Courses</h2>
    </div>
    <div class="course">
        <div class="packet">
            <div class="image">
                <img src="../assets/img/course-02-480x298.jpg" alt="">
            </div>
            <div class="info-course">
                <p>price</p>
            <p>text text text text</p>
            <div class="class">
                <p>lessons</p>
                <p>students</p>
            </div>
            </div>
        </div>
        <div class="packet">
            <div class="image">
                <img src="../assets/img/course-02-480x298.jpg" alt="">
            </div>
            <div class="info-course">
                <p>price</p>
            <p>text text text text</p>
            <div class="class">
                <p>lessons</p>
                <p>students</p>
            </div>
            </div>
        </div>
    </div>
    <div class="btn">
        <button>click</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppCenterTop",
};
</script>

<style lang="scss" scoped>
@import "../style/variable";

.center-top {
  width: $project-width;
  margin: $project-margin;
  padding: 4em 0;
  .text {
    text-align: center;
    margin-bottom: 1em;
  }
  .course{
      display: flex;
      flex-wrap: wrap;
      .packet{
          width: calc(100% / 2);
          display: flex;
          align-items: center;
          margin-top: 3em;
          img{
              width: 150px;
              height: 150px;
              border-radius: 50%;
              margin-right: 1em;
          }
      }
  }
  .btn{
      text-align: center;
      margin-top: 2em;
  }
}
</style>
