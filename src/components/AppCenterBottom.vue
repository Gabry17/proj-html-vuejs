<template>
  <div class="center-bottom">
    <div class="title">
      <p>enjoy reading on maxcoach</p>
      <h2>Latest on Our Blogs</h2>
    </div>
    <div class="blogs">
      <div class="card">
        <img src="../assets/img/artist-blog-03-480x325.jpeg" alt="artist" />
        <p>artist</p>
        <h3>Brush Strokes Energize Trees in Paintings</h3>
        <span>date </span>
        <span>views</span>
      </div>
      <div class="card">
        <img src="../assets/img/artist-blog-01-480x325.jpg" alt="artist" />
        <p>artist</p>
        <h3>Pocket-Sized Notebooks Hold Miniature Paintings</h3>
        <span>date </span>
        <span>views</span>
      </div>
      <div class="card">
        <img src="../assets/img/artist-blog-02-480x325.jpg" alt="artist" />
        <p>artist</p>
        <h3>Connection Between Self-Portraits and Identity</h3>
        <span>date </span>
        <span>views</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppCenterBottom",
};
</script>

<style lang="scss" scoped>
@import "../style/variable";

.center-bottom {
  padding: 4em;
  .title {
    width: $project-width;
    margin: $project-margin;
    text-align: center;
  }
  .blogs {
    width: $project-width;
    margin: $project-margin;
    display: flex;
    margin-top: 2em;
    .card {
      width: calc(100% / 3);
      margin-right: 1em;
      img {
        width: 100%;
      }
      p {
        margin-top: 0.5em;
      }
      h3 {
        margin: 0.5em 0;
      }
    }
  }
}
</style>
