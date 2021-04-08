<template>
  <div id="app">
    <Navbar/>
    <Carousel {slide}/>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Carousel from './components/Carousel.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Carousel
  }
}
</script>
