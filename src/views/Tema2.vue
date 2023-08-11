<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.pb-0.mb-0
      .titulo-principal__numero
        span 2
      h1 Sistema de emergencias médicas
    .row.align-items-center.bg-color4.pt-5.px-5
      .col-lg-4.mb-4.mb-lg-0
        figure(data-aos="fade-left")
          img(src='@/assets/curso/img4.png', style='width: 270px').m-auto
      .col-lg-8
        .row.px-4
          .col-12.p-5.bg-color5
            p.mb-0 El Ministerio de Salud y Protección Social, a través de la Resolución 926 de 2017, reglamenta el desarrollo y operación del Sistema de Emergencias Médicas (SEM) en Colombia, para garantizar una respuesta oportuna y efectiva a las situaciones de urgencia que se presenten en todo el territorio nacional.
          img(src='@/assets/curso/img12.png', style='width: 270px; position: relative; left: 50%; bottom: 20px;')
    separador.mb-5
    #t_2_1
    .titulo-segundo
      h2 2.1 ¿Qué es el SEM?
    p.mb-5 Conozcamos, con ayuda de la siguiente imagen, qué es el SEM y cómo está conformado.
    h5.mb-5 Sistema de Emergencias Médicas (SEM)
    .tarjeta--container.row.mb-5
      .col-md.tarjeta.color-primario.p-5
        .row.justify-content-center.mb-5
          .col-4
            figure
              img(src='@/assets/curso/img23.svg', alt='Texto que describa la imagen')
        h3.text-center.mb-5 Conformado por:
        ul.lista-ul.ms-5
          li 
            i.fas.fa-atom(style="color: #00BCD4")
            | Órganos de direccionamiento, a cargo del Ministerio de Salud y Protección Social, con el apoyo del Comité Nacional de Urgencias.
          li 
            i.fas.fa-atom(style="color: #00BCD4")
            | La coordinación no asistencial.
          li 
            i.fas.fa-atom(style="color: #00BCD4")
            | Operadores asistenciales.
      .col-md.tarjeta.color-acento-botones.p-5
        .row.justify-content-center.mb-5
          .col-4
            figure
              img(src='@/assets/curso/img24.svg', alt='Texto que describa la imagen')
        h3.text-center.mb-5 Objetivo:
        p.text-center Responder, de manera oportuna, a víctimas de enfermedad, paros cardiorrespiratorios, accidentes de tránsito o traumatismos, que requieran atención médica de urgencia, en lugares públicos y privados.
    p.mb-5 Se fija en cabeza de la entidad territorial, a través del Centro Regulador de Urgencias, Emergencias y Desastres — CRUE del territorio, de acuerdo con las funciones designadas en la resolución. Entre estas funciones se encuentran las siguientes:
    .row.align-items-center.mb-5
      .col-lg-7.mb-4.mb-lg-0
        .row.align-items-center.mb-4
          .col-auto.d-inline
            figure
              img(src='@/assets/curso/img25.svg', style='width: 50px').m-auto
          .col.p-4.bg-color6
            p.mb-0 Articulación del CRUE con el Número Único de Seguridad y Emergencias.
        .row.align-items-center.mb-4
          .col-auto.d-inline
            figure
              img(src='@/assets/curso/img26.svg', style='width: 50px').m-auto
          .col.p-4.bg-color6
            p.mb-0 Articular a los integrantes del SEM ante situaciones de emergencia o desastre, en el marco del Sistema Nacional de Gestión de Riesgo de Desastres.
        .row.align-items-center
          .col-auto.d-inline
            figure
              img(src='@/assets/curso/img27.svg', style='width: 50px').m-auto
          .col.p-4.bg-color6
            p.mb-0 Notificación y acceso.
      .col-lg-5
        figure(data-aos="fade-left")
          img(src='@/assets/curso/img5.png', style='width: 350px').m-auto
    .row.align-items-center.justify-content-center.bg-color3.px-5
      .col-12.mb-5
        p.mb-5 El acceso al SEM, por parte de la comunidad, se llevará a cabo a través de la línea 123 – Número Único de Seguridad y Emergencias (NUSE) donde se encuentre implementado, es decir, que cada entidad territorial deberá adelantar los trámites necesarios que garanticen la articulación del CRUE con el NUSE. En los casos donde el NUSE no opere, la notificación se podrá hacer a través de una línea gratuita, de fácil acceso y recordación para la comunidad.
        .h5.mb-5 ¿Cómo se implementa el SEM?
        TabsC.color-primario
          .py-3.py-md-4(titulo="Municipios y distritos de categoría especial")
            .row.align-items-center
              .col-md-6.mb-4.mb-md-0
                h4 Municipios y distritos de categoría especial
                p Deberán implementar el SEM en el territorio de su jurisdicción, teniendo en cuenta el análisis de la situación de salud, los antecedentes de emergencias y desastres, y las condiciones geográficas, para lo cual podrán construir, de manera autónoma, un Centro Regulador de Urgencias y Emergencias CRUE o suscribir convenios para tal fin, con el departamento.
              .col-md-6
                figure
                  img(src='@/assets/curso/img7.png', alt='Texto que describa la imagen')
          .py-3.py-md-4(titulo="Áreas metropolitanas y municipios de categorías diferentes")
            .row.align-items-center
              .col-md-6.mb-4.mb-md-0
                h4 Áreas metropolitanas y municipios de categorías diferentes, de manera independiente o asociados con otros municipios
                p Deberán implementar un SEM en su territorio. Se les facultará para construir Centros Reguladores de Urgencias y Emergencias CRUE, o suscribir convenios con el departamento de su jurisdicción.
              .col-md-6
                figure
                  img(src='@/assets/curso/img8.png', alt='Texto que describa la imagen')
    separador.mb-5
    #t_2_2
    .titulo-segundo
      h2 2.2 Tipos de escenarios
    figure
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/xDWKd5lfJOg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)        

</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass" scoped></style>
