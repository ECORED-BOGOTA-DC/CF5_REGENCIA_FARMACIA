<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 5
      h1 Botiquín
    .row.align-items-center.bg-color4.pt-5.px-5.mb-5
      .col-lg-7
        .tarjeta-avatar-b.mb-5(data-aos="fade-right")
          img(src='@/assets/curso/img52.svg' alt='Imágen decorativa')
          .tarjeta.tarjeta--azul(style="border: 3px dashed;")
            .p-4
              p El Botiquín es el conjunto de materiales, equipo y antisépticos que se utilizan para aplicar los primeros auxilios a un individuo que ha sufrido de un accidente o de una enfermedad súbita.
        .tarjeta-avatar-b.mb-5(data-aos="fade-right")
          img(src='@/assets/curso/img53.svg' alt='Imágen decorativa')
          .tarjeta.tarjeta--azul(style="border: 3px dashed;")
            .p-4
              p Es importante que el primer respondiente se prepare para la atención inicial de urgencias y tenga un botiquín de primeros auxilios en su casa, edificio o empresa.
        .tarjeta-avatar-b(data-aos="fade-right")
          img(src='@/assets/curso/img53-2.svg' alt='Imágen decorativa')
          .tarjeta.tarjeta--azul(style="border: 3px dashed;")
            .p-4
              p El modelo de botiquín se organiza de acuerdo con el tipo de actividad que se vaya a desarrollar, o el sitio en el cual se localiza.
      .col-lg-5
        figure(data-aos="fade-left")
          img(src='@/assets/curso/img11.png', style='width: 350px', alt='Imágen decorativa').m-auto
    p.mb-5 Los componentes de un botiquín son: 
    .row.align-items-center.bg-color2.px-5
      .col-lg-6.mb-5.mb-lg-0
        figure(data-aos="fade-right")
          img(src='@/assets/curso/img54.svg', style='width: 350px').m-auto
      .col-lg-6(data-aos="fade-left")
        LineaTiempoD.color-primario
          .row(numero="1" titulo="Antisépticos")
            .col-12
              p Sustancias cuyo objetivo es la prevención de infección en heridas superficiales (Yodopovidona solución y espuma).
          .row(numero="2" titulo="Jabones")
            .col-12
              p De tocador, barra o líquido, para el lavado de manos o heridas.
          .row(numero="3" titulo="Gasas")
            .col-12
              p Vendajes que se usan para limpiar y cubrir heridas o para detener hemorragias pequeñas.
          .row(numero="4" titulo="Esparadrapo")
            .col-12
              p Material que se utiliza para fijar vendas y afrontar el borde de las heridas.
          .row(numero="5" titulo="Agua estéril")
            .col-12
              p Se utiliza para lavar heridas y quemaduras.
          .row(numero="6" titulo="Vendas")
            .col-12
              p.mb-4 Parches que sirven para inmovilizar extremidades y realizar compresión, en caso de hemorragias. Pueden ser elásticas, de tela o de gasa.
              ul.lista-ul
                li.d-flex
                  i.fas.fa-atom(style="color: #00BCD4")
                  | 
                  p.mb-0 #[b Vendas adhesivas:] materiales como banditas y curitas. Son útiles para cubrir heridas superficiales.
          .row(numero="7" titulo="Otros elementos")
            .col-12
              p Guantes desechables, tapabocas, linterna, tijeras, termómetro digital, lista de teléfonos de emergencia, incluidos los de la EPS y la ARL, férulas o tablillas, inmovilizadores o cabestrillos, bolsas plásticas para desechos.
      p.my-5(data-aos="fade-left") Además, se recomienda tener en el lugar de trabajo, tablas espinales, collares, material de inmovilización y bioseguridad.
      .row.justify-content-center.align-items-center(data-aos="fade-left")
        .col-lg-auto.col-6.mb-lg-0.mb-4  
          img(src='@/assets/curso/img55.svg', style='width: 131px', alt='Imágen decorativa').px-0
        .col-lg.col-12.p-4
          p #[b Precaución]:
          ul.lista-ul
            li.d-flex
              i.fas.fa-atom(style="color: #7E5EE3")
              | Ubicar el botiquín en un sitio seguro, lejos del alcance de los niños y donde no represente ningún riesgo.
            li.d-flex
              i.fas.fa-atom(style="color: #7E5EE3")
              | Mantener el botiquín en un lugar fresco y seco.
            li.d-flex
              i.fas.fa-atom(style="color: #7E5EE3")
              | Todos los componentes deben estar debidamente empacados y marcados. En el caso de los líquidos, se recomienda utilizar envases plásticos, pues el vidrio se puede romper con facilidad.
            li.d-flex
              i.fas.fa-atom(style="color: #7E5EE3")
              | Periódicamente se deberá revisar el botiquín y sustituir aquellos componentes que se encuentren sucios, contaminados, dañados, o en los que no se pueda leer de forma clara, la fecha de vencimiento.

</template>

<script>
export default {
  name: 'Tema5',
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
