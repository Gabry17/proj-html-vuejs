<template>
  <div class="center-top">
    <div class="text">
      <p>choose a course to get started</p>
      <h2>Latest Featured <span>Courses</span></h2>
    </div>
    <div class="course">
      <AppPacket
        v-for="(item, index) in course"
        :key="index"
        :packetObj="item"
      />
    </div>
    <div class="btn">
      <button>
        View all courses <i class="fas fa-long-arrow-alt-right"></i>
      </button>
    </div>
  </div>
</template>

<script>
import AppPacket from "./AppPacket.vue";

export default {
  name: "AppCenterTop",
  components: {
    AppPacket,
  },
  data() {
    return {
      course: [
        {
          price: 40.0,
          image: 'course-02-480x298.jpg',
          text: "Learning to Write as a Professional Author",
          numberLessons: 20,
          numberStudents: 50,
        },
        {
          price: 0,
          image: 'stock-full-hd-03-480x298.jpg',
          text: "Customer-centric info-Tech Strategies",
          numberLessons: 24,
          numberStudents: 769,
        },
        {
          price: 19.0,
          image: 'stock-full-hd-04-480x298.jpg',
          text: "Open Programming Courses for Everyone: Python",
          numberLessons: 17,
          numberStudents: 62,
        },
        {
          price: 26.0,
          image: 'stock-full-hd-06-480x298.jpg',
          text: "Academic Listening and Note-taking",
          numberLessons: 14,
          numberStudents: 67,
        },
        {
          price: 39.0,
          image: 'course-featured-image-01-480x298.jpg',
          text: "Master jQuery in a Short Period of Time",
          numberLessons: 6,
          numberStudents: 51,
        },
        {
          price: 59.0,
          image: 'stock-full-hd-05-480x298.jpg',
          text: "Introducion to Javascript for Beginners",
          numberLessons: 14,
          numberStudents: 76,
        },
      ],
    };
  },
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
  span {
    color: $mountain-meadow-color;
  }
  .course {
    display: flex;
    flex-wrap: wrap;
  }
  .btn {
    text-align: center;
    margin-top: 2em;
  }
}
</style>
