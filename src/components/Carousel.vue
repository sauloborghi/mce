<template>
  <section class="carousel">
            <div class="owl-carousel owl-theme owl-home">
                <div class="item carousel-image" style="background-image: url('./assets/logo.jpg');">
                    <div class="overlay"></div>
                    <div class="container">
                        <div class="carousel-content">
                            <h1 class="title-carousel text-center">
                                Meu Centro Espírita
                            </h1>
                            <p class="subtitle-carousel text-center">
                                Conheça os Centros Espíritas mais próximos e assista ás suas palestras online.
                            </p>
                            <div class="btn-carousel-wrapper">
                                <button class="btn btn-1 btn-carousel">
                                    Saiba Mais
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="item carousel-image" style="background-image: url('../assets/logo.jpg');">
                    <div class="overlay"></div>
                    <div class="container">
                        <div class="carousel-content">
                            <h1 class="title-carousel text-center">
                                Baixe o nosso App!
                            </h1>
                            <p class="subtitle-carousel text-center">
                                Fique por dentro dos cronogramas de palestras e receba as nossas notificações.
                            </p>
                            <div class="btn-carousel-wrapper">
                                <button class="btn btn-1 btn-carousel">
                                    Baixar o App
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
</template>

<script>
export default {
  name: 'Carousel',
}
</script>