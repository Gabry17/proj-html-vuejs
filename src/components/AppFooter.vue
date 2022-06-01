<template>
  <footer>
    <div class="container-foot dimension d-flex">
      <div class="left">
        <h4>Address</h4>
        <div class="contact">
          <AppFooterAddress
            v-for="(item, index) in info"
            :key="index"
            :addressObj="item"
          />
        </div>
        <div class="icon">
          <i class="fab fa-facebook-square"></i>
          <i class="fab fa-twitter"></i>
          <i class="fab fa-instagram"></i>
          <i class="fab fa-linkedin"></i>
        </div>
      </div>
      <div class="right d-flex">
        <div class="explore">
          <h4>Explore</h4>
          <div class="components d-flex">
            <AppFooterExplore
              v-for="(item, index) in info"
              :key="index"
              :exploreObj="item"
            />
          </div>
        </div>
        <div class="information">
          <h4>Information</h4>
          <AppFooterInformation
            v-for="(item, index) in info"
            :key="index"
            :informationObj="item"
          />
        </div>
      </div>
    </div>
    <div class="copyright">
      <span
        ><i class="fas fa-copyright"></i> 2020 Maxcoach. All Rights
        Reserved</span
      >
    </div>
  </footer>
</template>

<script>
import AppFooterAddress from "./AppFooterAddress.vue";
import AppFooterExplore from "./AppFooterExplore.vue";
import AppFooterInformation from "./AppFooterInformation.vue";
export default {
  components: {
    AppFooterAddress,
    AppFooterExplore,
    AppFooterInformation,
  },
  name: "AppFooter",
  data() {
    return {
      info: [
        {
          contact: "382 NE 191st St # 87394 Miami, FL 33179-3899",
          explore: "Start here",
          information: "Membership",
        },
        {
          contact: "+1(305) 547-9909 (9am - 5pm EST, Monday - Friday)",
          explore: "Success story",
          information: "Purchase guide",
        },
        {
          contact: "support@maxcoach.com",
          explore: "Blog",
          information: "Privacy policy",
        },
        {
          explore: "courses",
          information: "Terms of services",
        },
        {
          explore: "About us",
        },
        {
          explore: "Contact us",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
@import "../style/variable";
footer {
  background-color: $hint-of-red-color;
  padding: 2em 0;
  h4 {
    margin: 0.5em 0;
  }
  .left {
    width: calc(100% / 2);
    .icon i {
      margin: 1em 1.5em 0 0;
      color: $gray-chateau-color;
    }
  }
  .explore {
    .components {
      flex-wrap: wrap;
    }
  }
  .copyright {
    text-align: center;
    margin-top: 2em;
    color: $gray-chateau-color;
  }
}
</style>
