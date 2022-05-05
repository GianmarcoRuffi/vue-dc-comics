!
<template>
  <body>
    <div class="main d-flex justify-content-around">
      <div class="row">
        <div class="col-2" v-for="(card, index) in miniCards" :key="index">
          <img :src="card.img" :alt="card.text" />
          <span>{{ card.text }}</span>
        </div>
      </div>
    </div>
  </body>
</template>

<script>
export default {
  name: "Merchandise",
  data() {
    return {
      miniCards: [
        {
          img: require("../assets/img/buy-comics-digital-comics.png"),
          text: "DIGITAL COMICS",
          url: "#",
        },

        {
          img: require("../assets/img/buy-comics-merchandise.png"),
          text: "DC MERCHANDISE",
          url: "#",
        },
        {
          img: require("../assets/img/buy-comics-subscriptions.png"),
          text: "Subscription",
          url: "#",
        },
        {
          img: require("../assets/img/buy-comics-shop-locator.png"),
          text: "Comic Shop Locator",
          url: "#",
        },
        {
          img: require("../assets/img/buy-dc-power-visa.svg"),
          text: "DC Power Visa",
          url: "#",
        },
      ],
    };
  },
};
</script>

<style scoped lang="scss">
@import "@/assets/merchandise.scss";
@import "@/assets/generals.scss";
</style>
