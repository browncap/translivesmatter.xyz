<template>
  <div>
    <Introduction />
    <Organizations />
  </div>
</template>

<script>
import Introduction from './components/Introduction.vue'
import Organizations from './components/Organizations.vue'

export default {
  name: 'Home',
  components: {
    Introduction,
    Organizations
  }
}
</script>

<style>
  .paragraph {
    width: 75%;
    margin: auto;
    padding: 0px;
  }

  .paragraph p {
    font-family: "OpenSans", Arial, Helvetica, sans-serif;
    font-size: 17px;
    color: white;
  }

  .constrain {
    margin:auto;
  }

  @media(min-width: 540px) {
    .paragraph {
      width: 60%;
      margin-bottom: 30px;
    }

    .paragraph p {
      font-size: 18px;
    }

    .constrain{
      width: 100%;
      max-width: 740px;
    }
  }
</style>
