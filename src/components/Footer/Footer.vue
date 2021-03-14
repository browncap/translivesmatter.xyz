<template>
  <footer id="footer">
    <a href="https://www.theycount.xyz"><p>Learn more</p></a>
    <span>|</span>
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

  #footer span {
    padding: 0px 5px;
    color: white;
    font-size:20px;
  }

  #footer a {
    color: white;
    text-decoration: none;
  }

  #footer a:visited {
    text-decoration: none;
  }
</style>
