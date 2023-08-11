<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5.bg-color1
  
    .titulo-principal
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .row
      .col-lg-4
        figure.mb-5(data-aos="fade-left")
          img(src='@/assets/curso/img1.png', style='width: 250px').m-auto
      .col-lg-8
        .h4 ¿Quién es el primer respondiente?
        p En este componente formativo, damos respuesta a esta pregunta, incluyendo cuál es la normatividad legal vigente que lo rige, y también los principios básicos con los que debe actuar ante situaciones de enfermedad súbita o lesiones, en clientes o usuarios al servicio farmacéutico/droguería.
        .cajon.color-primario.p-4.mb-4
          p.mb-0 También estudiaremos el #[b Sistema de Emergencias Médicas], conoceremos qué es riesgo y peligro, los diferentes tipos de accidentes, y finalizamos con los elementos básicos que debe contener un botiquín.
      .col-12
        p.mb-0 #[b ¡Muchos éxitos en este proceso de aprendizaje!]

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
