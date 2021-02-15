<template>
  <div id="app">
    <Navigation />
    <Jumbotron />
    <Carousel />
    <Footer />
  </div>
</template>

<script>
import Navigation from './components/Navigation.vue'
import Jumbotron from './components/Jumbotron.vue'
import Carousel from './components/Carousel.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Navigation,
    Jumbotron,
    Carousel,
    Footer
  }
}
</script>

<style scoped>

</style>
