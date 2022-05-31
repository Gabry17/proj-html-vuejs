<template>
  <div class="center">
    <div class="main">
      <h2>Why People Talk About MaxCoach?</h2>
      <div class="info">
        <img src="../assets/img/testimonial-avata-02.jpg" alt="freelancer" />
        <div class="text">
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Eligendi
            aperiam sequi dignissimos obcaecati sed dolores placeat, commodi ab
            quae illum quaerat officiis! Aperiam tempora sed beatae voluptate,
            optio maiores libero!
          </p>
          <p>
            MINA HOLLAGE <br />
            /freelancer
          </p>
        </div>
      </div>
      <div class="logo">
          <img src="../assets/img/client-logo-colored-01.png" alt="aqua">
          <img src="../assets/img/client-logo-colored-02.png" alt="adroll">
          <img src="../assets/img/client-logo-colored-03.png" alt="">
          <img src="../assets/img/client-logo-colored-04.png" alt="wooland">
          <img src="../assets/img/client-logo-colored-05.png" alt="bullfit">
          <img src="../assets/img/client-logo-colored-06.png" alt="sixbase">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppCenter",
};
</script>

<style lang="scss" scoped>
@import "../style/variable";
.center {
  background-color: $white-color;
  padding: 4em 0;
  .main {
    width: $project-width;
    margin: $project-margin;
    h2 {
      margin-bottom: 2em;
      text-align: center;
    }
    .info {
      display: flex;
      align-items: center;
      justify-content: space-around;
      margin-bottom: 3em;
      img{
          border-radius: 50%;
          width: 20%;
      }
      .text{
          width: 60%;
      }
    }
    .logo{
        display: flex;
        justify-content: space-between;
        align-items: center;
        img{
            height: 10%;
        }
    }
  }
}
</style>
