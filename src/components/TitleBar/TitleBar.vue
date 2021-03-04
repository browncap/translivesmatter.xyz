<template>
  <div class="constrain">
    <div class="imgContainer">
      <img :src="getImgUrl('logo.png')">
    </div>
  </div>
</template>

<script>
export default {
  name: "TitleBar",
  methods: {
    getImgUrl: function(path) {
      return require("@/assets/images/" + path);
    }
  }
}
</script>

<style scoped>

  .constrain{
    width: 90%;
  }

  .imgContainer {
    height: 71px;
    width: 100px;
    margin: 0px 0px 25px 0px;
    padding: 20px 0px 10px 0px;
  }

  @media(min-width: 540px) {
    .imgContainer {
      margin-bottom: 35px;
    }
  }

</style>
