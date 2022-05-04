<template>
  <div id="app">
    <Header />
    <MainContent />
    <Merchandise />
    <Footer />
    <BottomSocials />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import MainContent from "./components/MainContent.vue";
import Merchandise from "./components/Merchandise.vue";
import Footer from "./components/Footer.vue";
import BottomSocials from "./components/BottomSocials.vue";

export default {
  name: "App",
  components: { Header, MainContent, Merchandise, Footer, BottomSocials },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  @import url("https://fonts.googleapis.com/css2?family=Roboto&display=swap");

  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Roboto", sans-serif;
}
</style>
