<template>
  <div class="center-top">
    <div class="text">
      <p>choose a course to get started</p>
      <h2>Latest Featured <span>Courses</span></h2>
    </div>
    <div class="course">
      <div class="packet">
        <div class="image">
          <img src="../assets/img/course-02-480x298.jpg" alt="" />
        </div>
        <div class="info-course">
          <h3>price</h3>
          <p>text text text text</p>
          <div class="class">
            <span><i class="fas fa-file-alt"></i> 20 lessons </span>
            <span><i class="fas fa-user-alt"></i> 50 students</span>
          </div>
        </div>
      </div>
      <div class="packet">
        <div class="image">
          <img src="../assets/img/course-02-480x298.jpg" alt="" />
        </div>
        <div class="info-course">
          <h3>price</h3>
          <p>text text text text</p>
          <div class="class">
            <span><i class="fas fa-file-alt"></i> 20 lessons </span>
            <span><i class="fas fa-user-alt"></i> 50 students</span>
          </div>
        </div>
      </div>
    </div>
    <div class="btn">
      <button>
        View all courses <i class="fas fa-long-arrow-alt-right"></i>
      </button>
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
    p {
      color: $dove-gray-color;
    }
  }
  span,
  h3 {
    color: $mountain-meadow-color;
  }
  .course {
    display: flex;
    flex-wrap: wrap;
    .packet {
      width: calc(100% / 2);
      display: flex;
      align-items: center;
      margin-top: 3em;
      padding: 1em;
      p{
          margin: 1em 0;
      }
      img {
        width: 150px;
        height: 150px;
        border-radius: 50%;
        margin-right: 1em;
      }
      span{
          color: $dove-gray-color;
          margin-right: .5em;
      }
    }
    .packet:hover{
      background-color: $white-color;
      border-radius: 5px;
    }
  }
  .btn {
    text-align: center;
    margin-top: 2em;
  }
}
</style>
