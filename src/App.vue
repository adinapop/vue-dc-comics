<template>
  <div id="app">
    <Nav />
    <!-- Bindo il main al data che mi serve, in questo caso l'array -->
    <Main :comics = "comics" />  
    <Section />
    <FooterInfo />
    <FooterMedia />
  </div>

</template>

<script>
import Nav from './components/Nav.vue';
import Main from "./components/Main.vue";
import Section from "./components/Section.vue";
import FooterInfo from "./components/FooterInfo.vue";
import FooterMedia from "./components/FooterMedia.vue";
import ComicsData from "./jsons/dc-comics.json";

export default {
  name: 'App',
  components: {
    Nav,
    Main,
    Section,
    FooterInfo,
    FooterMedia,
  },
  data: function() {
    return {
      comics: ComicsData,
    }
  }
}
</script>

<style lang="scss">
@import "./style/app.scss";
@import url('https://fonts.googleapis.com/css2?family=Roboto+Condensed&display=swap');

</style>
