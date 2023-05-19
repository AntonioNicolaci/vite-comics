<script>
import Header from './components/Header.vue';
// import MainPage from './components/MainPage.vue';
import LinkBar from './components/LinkBar.vue';
import FooterPage from './components/FooterPage.vue';

export default {

  components: {
    Header,
    // MainPage,
    LinkBar,
    FooterPage,
  }
}
</script>

<template>
  <Header></Header>
  <!-- <MainPage /> -->
  <LinkBar />
  <FooterPage />
</template>

<style lang="scss">
  * {
    margin: 0;
    padding: 0;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  }
  a {
    text-decoration: none;
    color: #000;
  }
</style>
