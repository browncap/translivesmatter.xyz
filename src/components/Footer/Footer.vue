<template>
  <footer id="footer">
    <p>© Copyright 2021</p>
  </footer>
</template>

<script>
export default {
  name: "Footer"
}
</script>

<style scoped>
  #footer {
    height: 100px;
    color: white;
    text-align: center;
    margin-top: 25px;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  #footer p {
    font-family: "OpenSans", Arial, Helvetica, sans-serif;
    padding: 0px 5px;
    color: white;
  }
</style>
