<template>
  <div id="app">
    <Navbar/>
    <Carousel/>
    <Card/>
    <Form/>
    <Rodape/>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Carousel from './components/Carousel.vue'
import Card from './components/Card.vue'
import Form from './components/Form.vue'
import Rodape from './components/Rodape.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Carousel,
    Card,
    Form,
    Rodape
  }
}
</script>
