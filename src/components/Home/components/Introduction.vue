<template>
  <div class="constrain">

    <div class="titleHeader">
      <p>Support Trans Lives</p>
    </div>

    <div class="paragraph">
      <p>At least 44 transgender and gender non-conforming people were killed in the United States in 2020. Most of the victims were young Black and Latinx transgender women.</p>
    </div>

    <div class="paragraph">
      <p>Please consider donating to one of the following organizations.</p>
    </div>

  </div>
</template>

<script>
export default {
  name: "Introduction"
}
</script>

<style scoped>

  .titleHeader p {
    font-family: "Coustard", Arial, Helvetica, sans-serif;
    font-size: 24px;
    color: #F6A4EB;
    font-weight: 500;
    margin: 0px;
  }

  .secondaryParagraph p {
    margin: 17px 0px;
  }

  @media(min-width: 540px) {
    .titleHeader p {
      font-size: 32px;
      margin-bottom:40px;
    }
  }

</style>
