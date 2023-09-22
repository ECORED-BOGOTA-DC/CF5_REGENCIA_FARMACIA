<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5.bg-color1
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .row
      .col-12(data-aos="fade-right")
        figure.mb-4
          .video
            <iframe width="853" height="480" src="https://www.youtube.com/embed/OdQNJetD-lY?si=rZTNTK1qrkDoq8Sw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      .col-12
        p.text-center.mb-0(data-aos="fade-left") #[b ¡Muchos éxitos en este proceso de aprendizaje!]

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped>
.introduccion
</style>
