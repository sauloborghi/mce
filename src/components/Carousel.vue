<template>
  <div>
    <b-carousel
      id="carousel-1"
      v-model="slide"
      :interval="4000"
      controls
      indicators
      background="#ababab"
      img-width="1024px"
      img-height="48px"
      style="text-shadow: 1px 1px 2px #333;"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
    >
      <!-- Text slides with image -->
      <b-carousel-slide
        caption="Meu Centro Espírita"
        text="Conheça os Centros Espíritas mais próximos e assista ás suas palestras online."
        img-src="https://www.freewebheaders.com/wp-content/gallery/religion-size-1024x300/the-life-of-jesus-christ-website-header_size-1024x300.jpg"
      ></b-carousel-slide>

      <!-- Slides with custom text -->
      <b-carousel-slide
      caption="Baixe o nosso App!"
      text="Conheça os Centros Espíritas mais próximos e assista ás suas palestras online."
      img-src="https://usercontent.one/wp/www.giac-ltd.co.uk/wp-content/uploads/2017/06/contact-us-banner-1024x300.png">
      </b-carousel-slide>

      <!-- Slides with image only -->
      <b-carousel-slide
      caption="Conheça outros centros espíritas!"
      text="Conheça os Centros Espíritas mais próximos e assista ás suas palestras online."
      img-src="http://parksadventure.com/wp-content/uploads/2017/10/sunsets-header-2074-1024x300-2.jpg"></b-carousel-slide>

      <!-- Slides with img slot -->
      <!-- Note the classes .d-block and .img-fluid to prevent browser default image alignment -->
      <b-carousel-slide>
        <template #img>
          <img
            class="d-block img-fluid w-100"
            width="1024"
            height="480"
            src="https://usercontent.one/wp/www.giac-ltd.co.uk/wp-content/uploads/2017/06/contact-us-banner-1024x300.png"
            alt="image slot"
          >
        </template>
      </b-carousel-slide>
    </b-carousel>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        slide: 0,
        sliding: null
      }
    }
  }
</script>

<script>
export default {
  name: 'Carousel',
}
</script>