<template>
  <div class="packet">
    <div class="image">
      <img :src='require(`../assets/img/${packetObj.image}`)' alt="" />
    </div>
    <div class="info-course">
      <h3>{{ packetObj.price === 0 ? "Free" : packetObj.price + ".00" }}</h3>
      <p>{{ packetObj.text }}</p>
      <div class="class">
        <span><i class="fas fa-file-alt"></i> {{ packetObj.numberLessons }} lessons </span>
        <span><i class="fas fa-user-alt"></i> {{ packetObj.numberStudents }} students</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppPacket",
  props: {
    packetObj: Object,
  }
};
</script>

<style lang="scss" scoped>
@import "../style/variable";

.packet {
  width: calc(100% / 2);
  display: flex;
  align-items: center;
  margin-top: 3em;
  padding: 1em;
  h3 {
    color: $mountain-meadow-color;
  }
  p {
    margin: 1em 0;
  }
  img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    margin-right: 1em;
  }
  span {
    color: $dove-gray-color;
    margin-right: 0.5em;
  }
}
.packet:hover {
  background-color: $white-color;
  border-radius: 5px;
}
</style>
