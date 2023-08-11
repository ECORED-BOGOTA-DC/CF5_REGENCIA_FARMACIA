<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .row.align-items-center.bg-color9.px-5.mb-5
      .titulo-principal
        .titulo-principal__numero
          span 4
        h1 Accidentes
      .row.align-items-center
        .col-lg-4.mb-4.mb-lg-0
          figure(data-aos="fade-left")
            img(src='@/assets/curso/img10.png', style='width: 350px').m-auto
        .col-lg-8
          .row.px-4
            .col-12.p-5.bg-color5
              p.mb-0 La Organización Mundial de la Salud, define a un accidente como: un acontecimiento imprevisto, independiente de la voluntad humana, incitado por una fuerza exterior que actúa rápidamente y se manifiesta por la aparición de lesiones orgánicas o trastornos mentales.
            img(src='@/assets/curso/img13.png', style='width: 270px; position: relative; left: 50%; bottom: 30px;')
          .cajon.color-primario.p-4.mb-4
            p.mb-0 De acuerdo con el registro de llamadas a la línea 123, en el 2016, en ciudades como Bogotá, Medellín y Barranquilla, se determinó la tasa de incidencia de los diferentes tipos de accidentes, de la siguiente manera:
        .col-12
          figure(data-aos="fade-right")
            img(src='@/assets/curso/img40.svg', style='width: 950px').m-auto
    p.mb-5 Los accidentes pueden ser de diferentes tipos:
    AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
      .row(titulo="Accidentes domésticos")
        .col-12
          p Un accidente en el hogar se refiere a cualquier hecho o fenómeno traumático espontáneo que le sucede al individuo sano, o bien, en el curso de una enfermedad; estos accidentes se consideran una situación de salud pública, debido a que se acostumbran presentar, en la mayoría de los casos, con los niños y/o los adultos mayores, generalmente causados por circunstancias ambientales o conductas personales que se pueden prevenir.
          p.mb-4 Las causas de los accidentes domésticos suelen ser:
          .row.justify-content-center
            .col-10
              .row.align-items-center
                .col-auto.d-inline
                  figure
                    img(src='@/assets/curso/img41.svg', style='width: 100px').m-auto
                .col
                  p.mb-0 Las caídas, debido a suelos resbaladizos, al tratar de alcanzar objetos de forma inadecuada (con una silla, por ejemplo, en lugar de una escalera).
              hr
              .row.align-items-center
                .col-auto.d-inline
                  figure
                    img(src='@/assets/curso/img42.svg', style='width: 100px').m-auto
                .col
                  p.mb-0 Las intoxicaciones con los productos de limpieza mal etiquetados, reembolsados o al alcance de los niños. También se presentan por mal almacenamiento de medicamentos.
              hr
              .row.align-items-center
                .col-auto.d-inline
                  figure
                    img(src='@/assets/curso/img43.svg', style='width: 100px').m-auto
                .col
                  p.mb-0 Las quemaduras suelen estar ocasionadas por el contacto o la proyección de objetos y/o líquidos a temperaturas elevadas.
              hr
              .row.align-items-center
                .col-auto.d-inline
                  figure
                    img(src='@/assets/curso/img44.svg', style='width: 100px').m-auto
                .col
                  p.mb-0 La electrocución puede ocasionarse cuando se manipulan, de forma incorrecta, los elementos eléctricos, introducción de pinzas o ganchos en los enchufes.
              hr
              .row.align-items-center
                .col-auto.d-inline
                  figure
                    img(src='@/assets/curso/img45.svg', style='width: 100px').m-auto
                .col
                  p.mb-0 Los golpes producidos generalmente con objetos fijos, como, por ejemplo, muebles, puertas y ventanas.
              hr
      .row(titulo="Accidentes de tránsito")
        .col-12
          p Teniendo en cuenta el Código Nacional de Tránsito, Cap. I, art. 2:
          .row.justify-content-center.mb-5
            .col-lg-11
              .bloque-texto-d.color-secundario.p-4
                .bloque-texto-d__texto.mb-2
                  i.fas.fa-quote-left
                  h3.text-regular #[b Un accidente de tránsito es un evento generalmente involuntario, generado al menos por un vehículo en movimiento, que causa daños a personas y bienes involucrados en él, e igualmente afecta la normal circulación de los vehículos que se movilizan por la vía o vías comprendidas en el lugar o dentro de la zona de influencia del hecho.]
                  i.fas.fa-quote-right.d-flex.justify-content-end
          p.mb-5 Los tipos de accidentes de tránsito que se presentan con mayor frecuencia son:
          figure.mb-5
            img(src='@/assets/curso/img46.svg', style='width: 950px').m-auto
          .cajon.color-primario.p-4.mb-4
            p.mb-0 Los accidentes de tránsito son la séptima causa de morbilidad en el planeta y la primera causa de muerte de las personas menores de 40 años a escala mundial. En promedio, 1,3 millones de personas en el mundo mueren al año por accidentes de tránsito.
          p La mayoría de los accidentes de tránsito tienen un factor de riesgo en común, el FACTOR HUMANO:
          ul.lista-ul.ms-5.mb-4
            li 
              i.fas.fa-atom(style="color: #00BCD4")
              | Conducir bajo los efectos de medicamentos, sustancias psicoactivas y licor (mayor causalidad de accidentes).
            li 
              i.fas.fa-atom(style="color: #00BCD4")
              | Llevar a cabo maniobras imprudentes y por descuido por parte del conductor.
            li 
              i.fas.fa-atom(style="color: #00BCD4")
              | Adelantar en espacios prohibidos (alto riesgo de choque frontal muy grave).
            li 
              i.fas.fa-atom(style="color: #00BCD4")
              | Desobedecer las señales de tránsito: pasarse un semáforo en rojo.
            li 
              i.fas.fa-atom(style="color: #00BCD4")
              | Circular por el carril contrario (en una curva o en un cambio de rasante).
            li 
              i.fas.fa-atom(style="color: #00BCD4")
              | Conducir con exceso de velocidad (puede producir vuelcos, salida del automóvil de la carretera o derrapes).
            li 
              i.fas.fa-atom(style="color: #00BCD4")
              | Utilizar de forma incorrecta las luces del vehículo, en especial de noche.
            li 
              i.fas.fa-atom(style="color: #00BCD4")
              | Peatones que cruzan las calles por lugares incorrectos, que se distraen con juegos en las carreteras o que arrojan objetos resbaladizos al carril de circulación (aceites, piedras).
            li 
              i.fas.fa-atom(style="color: #00BCD4")
              | Falta de experiencia al volante por parte del conductor.
            li 
              i.fas.fa-atom(style="color: #00BCD4")
              | Condiciones no aptas de salud física y mental/emocional del conductor o del peatón (ceguera, daltonismo, sordera, etc.).
            li 
              i.fas.fa-atom(style="color: #00BCD4")
              | Cansancio del conductor, como producto de la apnea o la falta de sueño.
          p Otros factores de riesgo para los accidentes de tránsito son:
          .tarjeta--container.row.mb-5
            .col-md.tarjeta.color-primario.p-5
              .row.justify-content-center.mb-5
                .col-4
                  figure
                    img(src='@/assets/curso/img47.svg', alt='Texto que describa la imagen')
              h3.text-center.mb-5 Los factores mecánicos
              .row.justify-content-center.mb-5
                .col-8
                  ul.lista-ul.ms-5
                    li 
                      i.fas.fa-atom(style="color: #00BCD4")
                      | Mal estado de la vía y del vehículo.
                    li 
                      i.fas.fa-atom(style="color: #00BCD4")
                      | Vehículo en condiciones inadecuadas para operar: averías en los sistemas de frenos, de dirección o de suspensión.
                    li 
                      i.fas.fa-atom(style="color: #00BCD4")
                      | Mantenimiento inadecuado del vehículo.
            .col-md.tarjeta.color-acento-botones.p-5
              .row.justify-content-center.mb-5
                .col-4
                  figure
                    img(src='@/assets/curso/img48.svg', alt='Texto que describa la imagen')
              h3.text-center.mb-5 Los factores climáticos
              .row.justify-content-center.mb-5
                .col-6
                  ul.lista-ul.ms-5
                    li 
                      i.fas.fa-atom(style="color: #00BCD4")
                      | Niebla.
                    li 
                      i.fas.fa-atom(style="color: #00BCD4")
                      | Humedad.
                    li 
                      i.fas.fa-atom(style="color: #00BCD4")
                      | Derrumbes.
                    li 
                      i.fas.fa-atom(style="color: #00BCD4")
                      | Zonas inestables.
                    li 
                      i.fas.fa-atom(style="color: #00BCD4")
                      | Hundimientos.
      .row(titulo="Accidentes laborales")
        .row.align-items-center
          .col-lg-8.mb-4.mb-lg0
            p De acuerdo con el Artículo 3 de la Ley 1562 de 2012, se define a los accidentes laborales como: todo acontecimiento repentino que se presente por causa o con ocasión del trabajo, y que provoque en el trabajador una lesión orgánica, una perturbación funcional o psiquiátrica, una invalidez o la muerte. Los 5 sectores económicos que concentran la mayor parte de los accidentes laborales son: minas y canteras, transporte, almacenamiento y comunicaciones, construcción, agricultura, ganadería, caza y silvicultura e inmobiliario.
          .col-lg-4
            figure
              img(src='@/assets/curso/img49.svg', style='width: 350px').m-auto
      .row(titulo="Accidents deportivos")
        .row.justify-content-center
          p Son lesiones corporales traumáticas que tienen su origen en una causa ajena a la voluntad del deportista, externa, fortuita, súbita y violenta.
          .col-10
            .row.align-items-center
              .col-auto.d-inline
                figure
                  img(src='@/assets/curso/img50.svg', style='width: 100px').m-auto
              .col
                p.mb-0 Por ejemplo, una caída, un impacto contra un objeto -como el poste de una portería- o un choque entre dos deportistas, son ciertamente accidentes deportivos.
            hr
            .row.align-items-center
              .col-auto.d-inline
                figure
                  img(src='@/assets/curso/img51.svg', style='width: 100px').m-auto
              .col
                p.mb-0 Además, se pueden encontrar las lesiones deportivas, que son el resultado de estados crónicos o patológicos como consecuencia de la práctica de cualquier deporte.
            hr
        .cajon.color-primario.p-4
          p.mb-0 Son lesiones deportivas accidentales no traumáticas, una contractura muscular, una rotura de un ligamento o un tendón, una fascitis plantar o el codo de tenista, que tienen su origen por una sobrecarga del tejido muscular, tendón o ligamento.

</template>

<script>
export default {
  name: 'Tema4',
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
