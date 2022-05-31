<template>
  <footer>
    <div class="container-foot">
      <div class="left">
        <h4>Address</h4>
        <div class="contact">
          <ul>
            <li>382 ne 191 shs dhdh dhd</li>
            <li>number</li>
            <li>email</li>
          </ul>
        </div>
        <div class="icon">
          <i class="fab fa-facebook-square"></i>
          <i class="fab fa-twitter"></i>
          <i class="fab fa-instagram"></i>
          <i class="fab fa-linkedin"></i>
        </div>
      </div>
      <div class="right">
        <div class="explore">
          <h4>Explore</h4>
          <ul>
            <li>Start here</li>
            <li>Blog</li>
            <li>About us</li>
            <li>Success story</li>
            <li>Courses</li>
            <li>Contact us</li>
          </ul>
        </div>
        <div class="information">
            <h4>Information</h4>
          <ul>
            <li>Membership</li>
            <li>Purchase guide</li>
            <li>Privacy policy</li>
            <li>Terms of services</li>
          </ul>
        </div>
      </div>
    </div>
    <div class="copyright">
        <span><i class="fas fa-copyright"></i> 2020 Maxcoach. All Rights Reserved</span>
    </div>
  </footer>
</template>

<script>
export default {
  name: "AppFooter",
};
</script>

<style lang="scss" scoped>
@import "../style/variable";
footer {
  background-color: $hint-of-red-color;
  padding: 2em 0;
  .container-foot {
    width: $project-width;
    margin: $project-margin;
    display: flex;
    h4,
    li {
      margin: 0.5em 0;
    }
    .left {
        width: calc(100% /2);
      .icon i {
        margin: 1em 1.5em 0 0;
      }
    }
    .right{
        display: flex;
        .explore{
        ul{
            display: flex;
            flex-wrap: wrap;
            li{
                width: calc(100% / 2);
            }
        }
    }
    }
  }
  .copyright{
      text-align: center;
      margin-top: 2em;
  }
}
</style>
