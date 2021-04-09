<template>
  <div id="app">
    <Navbar/>
    <Carousel/>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Carousel from './components/Carousel.vue'
import Card from './components/Card.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Carousel,
    Card
  }
}
</script>
