<script>
import Header from './components/Header.vue';
import ContentPage from './components/ContentPage.vue'
import LinkBar from './components/LinkBar.vue';
import FooterPage from './components/FooterPage.vue';

export default {
  
  components: {
  Header,
  ContentPage,
  LinkBar,
  FooterPage,
}
}
</script>

<template>
  <Header></Header>
  <ContentPage />
  <LinkBar />
  <FooterPage />
</template>

<style lang="scss">
* {
  margin: 0;
  padding: 0,
}
button {
        background-color: rgba(0, 0, 0, 0);
        border: none;
}
</style>
