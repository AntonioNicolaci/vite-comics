<script>
import Header from './components/Header.vue';
import ContentPage from './components/ContentPage.vue'
import LinkBar from './components/LinkBar.vue';

export default {
  
  components: {
  Header,
  ContentPage,
  LinkBar,
}
}
</script>

<template>
  <Header></Header>
  <ContentPage />
  <LinkBar />
</template>

<style scoped>

</style>
