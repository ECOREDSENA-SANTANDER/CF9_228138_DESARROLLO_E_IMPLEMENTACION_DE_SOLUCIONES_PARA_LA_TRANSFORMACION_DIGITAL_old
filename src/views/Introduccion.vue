<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
  
    .bloque1.p-0.mb-5
      .bloque-texto-b.color-secundario.p-3.px-0.mb-0(data-aos="fade-left")
        .bloque-texto-b__texto
          .row.justify-content-center.align-items-center.d-flex
            .col-lg-10.col-12
                p En este componente formativo, tendrá la capacidad de crear aplicaciones que gestionen recursos IoT a través de sistemas de información basado en tecnología de punta, así mismo, dispondrá de la apropiación de conocimiento para realizar pruebas del código desarrollado o de otras soluciones que analicen y midan la eficacia y eficiencia de un aplicativo.<br><br>La tecnología IoT son dispositivos que están conectados a una red de datos sea Internet o local, a nivel de desarrollo de software muchas aplicaciones se deben crear para la interacción con estos dispositivos. Veamos este tipo de programación:
            .col-lg-2.col-6.px-5
                img.mb-0(alt="" src="@/assets/curso/portada/img01.svg")
  
    figure.mb-4(data-aos="zoom-in")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/iSWz9b7HCEo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      
</template>
<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
