!
<template>
  <body>
    <div class="main">
      <div class="row placeholder">
        <div
          class="col-2"
          v-for="(merchandiseLink, index) in merchandiseLinks"
          :key="index"
        ></div>
      </div>
    </div>
  </body>
</template>

<script>
export default {
  name: "Links",
  data() {
    return {
      merchandiseLinks: [
        {
          img: require("../assets/img/buy-comics-digital-comics.png"),
          url: "#",
        },

        {
          img: require("../assets/img/buy-comics-merchandise.png"),
          url: "#",
        },
        {
          img: require("../assets/img/buy-comics-subscriptions.png"),
          url: "#",
        },
        {
          img: require("../assets/img/buy-comics-shop-locator.png"),
          url: "#",
        },
        {
          img: require("../assets/img/buy-dc-power-visa.svg"),
          url: "#",
        },
      ],
    };
  },
};
</script>

<style scoped lang="scss">
@import "@/assets/merchandise.scss";
// @import "@/assets/generals.scss";
</style>
