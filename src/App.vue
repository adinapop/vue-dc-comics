<template>
  <div id="app">
    <Nav />
    <Main />
    <Section />
    <FooterInfo />
    <FooterMedia />
  </div>
  
</template>

<script>
import Nav from './components/Nav.vue'
import Main from "./components/Main.vue"
import Section from "./components/Section.vue"
import FooterInfo from "./components/FooterInfo.vue"
import FooterMedia from "./components/FooterMedia.vue"

export default {
  name: 'App',
  components: {
    Nav,
    Main,
    Section,
    FooterInfo,
    FooterMedia,
  }
}
</script>

<style lang="scss">
@import "./style/app.scss";
@import url('https://fonts.googleapis.com/css2?family=Roboto+Condensed&display=swap');

</style>
