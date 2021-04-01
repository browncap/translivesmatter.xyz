<template>
  <div class="constrain">
    <ul>
      <li v-for="org in organizations" :key="org">
        <div class="organization" v-on:click="goTo(org.link)">
          {{ org.name }}
        </div>
      </li>
    </ul>
  </div>

</template>

<script>
export default {
  name: "Counted",
  methods: {
    goTo: function(url) {
      return window.open(url);
    }
  },
  data: function () {
    return {
      organizations: [
        {name: "For The Gworls", link: "https://www.forthegworls.party/donate"},
        {name: "Homeless Black Trans Women Fund", link: "https://www.gofundme.com/f/p6q5sm-homeless-black-trans-women-fund?utm_source=twitter&utm_medium=social&utm_campaign=m_pd+share-sheet"},
        {name: "TransLatin@ Coalition", link: "https://www.translatinacoalition.org/donate"},
        {name: "The Okra Project", link: "https://www.theokraproject.com/"},
        {name: "Mermaids", link: "https://mermaidsuk.org.uk/donate/"},
        {name: "Transgender Law Center", link: "https://transgenderlawcenter.org/donate"},
        {name: "Trans Women of Color Collective", link: "https://www.twocc.us/donate/"},
        {name: "Black Visions", link: "https://www.blackvisionsmn.org/home1"},
        {name: "Trans Youth Equality Foundation", link: "http://www.transyouthequality.org/donate"},
        {name: "SNaP Co.", link: "https://www.snap4freedom.org/about"},
        {name: "Emergency Release Fund", link: "https://emergencyreleasefund.com/contribute/"},
        {name: "The Transgender District", link: "https://www.transgenderdistrictsf.com/donate"},
        {name: "Marsha P. Johnson Institute", link: "https://marshap.org/donate/"},
        {name: "TGI Justice", link: "http://www.tgijp.org/donate.html"},
        {name: "Black Trans Travel Fund", link: "https://www.blacktranstravelfund.com/donate"},
        {name: "Black Trans Femmes in the Arts", link: "https://www.artsbusinesscollaborative.org/fiscal-sponsorship/btfa-collective"},
        {name: "The Audre Lorde Project", link: "https://alp.org/civicrm/contribute/transact?reset=1&id=5"},
        {name: "Human Rights Campaign", link: "https://give.hrc.org/page/62714/donate/1?ea.tracking.id=or_gnr_hrc_homepage2020"},
        {name: "Latino Equality Alliance", link: "https://latinoequalityalliance.nationbuilder.com/donate"},
        {name: "INCITE!", link: "https://incite-national.org/donate/"},
        {name: "G.L.I.T.S", link: "https://www.glitsinc.org/donations"},
        {name: "LGBTQ Freedom Fund", link: "https://www.lgbtqfund.org/donate-1/"},
        {name: "Lavender Rights Project", link: "https://www.lavenderrightsproject.org/donate-1"},
        {name: "National Black Justice Coalition", link: "https://nbjc.org/nbjc-donate/"},
        {name: "BreakOUT!", link: "https://youthbreakout.kindful.com/"},
        {name: "House of GG", link: "https://houseofgg.org/donate/"},
        {name: "Princess Janae Place", link: "http://princessjanaeplace.org/index.php/about-us/our-mission.html"},
        {name: "Black AIDS Institute", link: "https://blackaids.org/donate/"},
        {name: "The Trans Justice Funding Project", link: "https://www.transjusticefundingproject.org/donate-now/"}
      ]
    }
  }
}
</script>

<style scoped>

  .organization {
    font-family: "Coustard", Arial, Helvetica, sans-serif;
    font-size: 16px;
    border-style: solid;
    border-width: 2px;
    width: 77%;
    margin: auto;
    margin-top: 12px;
    padding: 9px 4px 8px 4px;
    border-color: #F6A4EB;
    color: #F6A4EB;
  }

  .organization:hover {
    border-color: #67e5db;
    background-image: linear-gradient(#6772E5, 75%, #a067e5);
    color: #67e5db;
    cursor: pointer;
  }

  ul {
    list-style-type: none;
    padding: 0px;
    margin: auto;
    margin-top: 25px;
  }

  @media(min-width: 540px) {
    .organization {
      padding: 16px 4px 14px 4px;
      font-size: 19px;
    }
  }

</style>
