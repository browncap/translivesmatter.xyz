<template>
  <div id="app">
    <div class="container">
      <TitleBar />
      <Home />
      <Footer />
    </div>
  </div>
</template>

<script>
import TitleBar from '@/components/TitleBar/TitleBar.vue'
import Home from '@/components/Home/Home.vue'
import Footer from '@/components/Footer/Footer.vue'

export default {
  name: 'App',
  components: {
    TitleBar,
    Home,
    Footer
  }
}
</script>

<style>
  #app {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
  }

  html, body{
    color:#555;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 16px;
    line-height:1.6em;
    margin:0;
    height:100%;
  }

  img {
    width: 100%;
  }

  .container{
    position: relative;
    min-height: 100vh;
    background-image: linear-gradient(#6772E5, 98%, #a067e5);
  }

  @font-face {
    font-family: "Coustard";
    src: local("Coustard"),
    url(./assets/fonts/Coustard/Coustard-Regular.ttf) format("truetype");
  }

  @font-face {
    font-family: "OpenSans";
    src: local("OpenSans"),
    url(./assets/fonts/OpenSans/OpenSans-Regular.ttf) format("truetype");
  }

</style>
