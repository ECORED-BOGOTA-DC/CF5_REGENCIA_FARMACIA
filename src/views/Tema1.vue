<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal
      .titulo-principal__numero
        span 1
      h1 Normatividad legal vigente para el primer respondiente
    p.mb-5 ¿Sabías que todos los días, los individuos y la comunidad, en general, están sujetos a una enorme cantidad de intimidaciones de procedencia natural y a otras tantas más, provocadas por los seres humanos?
    figure(data-aos="fade-left")
      img(src='@/assets/curso/img2.svg', style='width: 950px').m-auto

    .row.align-items-center.bg-color2.px-5
      .col-12
        .row
          .col-12
            p En alguna circunstancia, podríamos ser testigos de incidentes o contingencias en el hogar, en la vía, en el trabajo, en la academia y, por lo tanto, debemos prepararnos para enfrentarlos y controlarlos desde un inicio.
          .col-lg-4.mb-4.mb-lg-0
            figure(data-aos="fade-right")
              img(src='@/assets/curso/img2.png', style='width: 350px').m-auto
          .col-lg-8
            p.mb-4 Los escrutinios señalan cómo una gran cantidad de las causas de mortandad, en los territorios, pueden prevenirse. Según datos del DANE y del Ministerio de Salud y Protección Social, la Enfermedad Isquémica y la Cerebrovascular se adueñan, de los dos primeros lugares, como causa de muerte en ciudades como Bogotá, Medellín o Barranquilla; les siguen las agresiones o violencia y una cantidad substancial de accidentes de tránsito. Con frecuencia, estas muertes o accidentes, podrían haberse evitado si se hubieran llevado a cabo las medidas preventivas, acertadas y convenientes.
            .cajon.color-primario.p-4
              p.mb-0 En el actual Sistema de Emergencias Médicas Colombianas y de acuerdo con la Resolución 926 del 2017 del Ministerio de Salud y Protección Social, “#[i #[b por la cual se reglamenta el desarrollo y operación del Sistema de Emergencias Médicas]]”, la atención de un lesionado, durante una emergencia, implica desde el punto de vista legal la aplicación de unos deberes y derechos, tanto para la víctima como para el auxiliador.
      separador
    #t_1_1
    .titulo-segundo
      h2 1.1  Primer respondiente
    p #[b ¿Sabes quien es el primer respondiente?]
    .row.justify-content-center.mb-5
      .col-lg-11
        .bloque-texto-d.color-secundario.p-4
          .bloque-texto-d__texto.mb-2
            i.fas.fa-quote-left
            h3.text-regular Primer respondiente. Es la persona capacitada que en forma solidaria decide participar en la atención inicial de alguien que ha sufrido una alteración de la integridad física y/o mental, y puede, o no, ser un profesional de la salud. Activará el SEM, apoyará en la valoración de los riesgos asociados al evento y brindará ayuda inicial al afectado.
            i.fas.fa-quote-right.d-flex.justify-content-end
          .bloque-texto-d__autor 
            .h6.mb-0 - Artículo 13. Resolución 926 del 2017
    .tarjeta.bg-color8.p-4.p-md-5(data-aos="fade-left")
      .row.justify-content-around.align-items-center
        .col-8.col-sm-6.col-md-4.mb-4.mb-md-0
          img(src="@/assets/curso/img4.svg")
        .col-md.col-lg-6
          .titulo-segundo
            h3 Tenga en cuenta
          p El desconocimiento de los límites en la atención básica por parte de los primeros respondientes, conlleva al deterioro del estado de salud de la persona con patología médica o traumática; esto puede suceder por “exceso o por defecto” en las acciones para la estabilización del lesionado.
          p.mb-4 La siguiente imagen nos presenta más información sobre el primer respondiente.
          a.boton.color-acento-contenido.texto-blanco(:href="obtenerLink('/downloads/anexo2.pdf')" target="_blank" type="application/pdf")
            span Descargar
            i.fas.fa-file-download
    separador.mb-5
    #t_1_2
    .titulo-segundo
      h2 1.2  Código Penal Colombiano
    p.mb-5 Es importante resaltar y aclarar que el Código Penal Colombiano:
    .tarjeta--container.row.mb-5
      .col-md.tarjeta.color-primario.p-5
        .row.justify-content-center.mb-5
          .col-4
            figure
              img(src='@/assets/curso/img5.svg', alt='Texto que describa la imagen')
        h3.text-center.mb-0 Artículo 131
        h4.text-center.mb-5 Omisión de socorro
        p.text-center (Penas aumentadas por el artículo 14 de la ley 890 de 2004) El que omitiere, sin justa causa, auxiliar a una persona cuya vida o salud se encontrare en grave peligro, incurrirá en prisión de treinta y dos (32) a setenta y dos (72) meses. 
      .col-md.tarjeta.color-acento-botones.p-5
        .row.justify-content-center.mb-5
          .col-4
            figure
              img(src='@/assets/curso/img6.svg', alt='Texto que describa la imagen')
        h3.text-center.mb-0 Artículo 120
        h4.text-center.mb-5 Lesiones culposas
        p.text-center (Penas aumentadas por el artículo 14 de la ley 890 de 2004) El que por culpa cause a otro alguna de las lesiones a las que se refieren los artículos anteriores, incurrirá en la respectiva pena disminuida de las cuatro quintas, a las tres cuartas partes.
    p.mb-5 Para poseer una mejor comprensión del párrafo anterior, debemos tener claros varios conceptos que estudiaremos a continuación.
    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
      .row(titulo="Culpa")
        .col-12
          p La culpa es definida como una acción criminal que se lleva a cabo sin tener el cuidado necesario para prevenir y eludir el daño. Se manifiesta por imprudencia, descuido, ineptitud, abandono.
          p Las formas en que se presenta la culpa son:
          .row.justify-content-center
            .col-11
              .row.align-items-center
                .col-auto.d-inline
                  figure
                    img(src='@/assets/curso/img7.svg', style='width: 100px')
                .col
                  p.mb-0 #[b Negligencia]:  indolencia en el actuar. Olvido consciente, descuido por ineptitud, o dejar de cumplir con un acto que exige el deber práctico. En cuanto a materia penal, es condenable. #[b Por ejemplo]: extraer de un vehículo accidentado al lesionado sin ningún tipo de ayuda o dispositivo médico, acción que genere complicaciones o secuelas posteriores.
              hr
              .row.align-items-center
                .col-auto.d-inline
                  figure
                    img(src='@/assets/curso/img8.svg', style='width: 100px')
                .col
                  p.mb-0 #[b Imprudencia]: condenable e inadmisible negligencia, y descuido de las precauciones que la prudencia ordinaria aconseja, y que encauza a ejecutar actos que se llevan a cabo sin la diligencia correspondiente y que son presumibles desde un punto de vista objetivo, siendo considerados como delito. #[b Por ejemplo]: en un accidente de motocicleta, retirar el casco del lesionado para saber si está sangrando.
              hr
              .row.align-items-center
                .col-auto.d-inline
                  figure
                    img(src='@/assets/curso/img9.svg', style='width: 100px')
                .col
                  p.mb-0 #[b Impericia]: insuficiencia de pericia, sabiduría, práctica, experiencia y habilidad en una ciencia o un arte. #[b Por ejemplo]: aplicar o utilizar un torniquete en una lesión hemorrágica leve, sin tener la habilidad técnica de realizarlo, puede generar la pérdida o amputación del miembro afectado.
              hr
              .row.align-items-center
                .col-auto.d-inline
                  figure
                    img(src='@/assets/curso/img10.svg', style='width: 100px')
                .col
                  p.mb-0 #[b Abandono]: aespués de iniciada la atención, esta se debe seguir proporcionando hasta que la responsabilidad por la salud del paciente sea transferida a un profesional competente de un nivel igual o superior. #[b Por ejemplo]: cuando se aplica un medicamento con o sin fórmula médica, la persona inicia una reacción anafiláctica, aparentemente leve, y se deja ir para su residencia, donde muere por paro respiratorio.
      div(titulo="Dolo")
        .row
          .col-12
            p El Código Penal Colombiano establece en su artículo 22 la definición de dolo, como: la conducta de realizar cualquier hecho constitutivo de infracción penal, de forma intencional.
            p.mb-5 Existen tres tipos de dolo:
            figure.mb-5
              img(src='@/assets/curso/img11.svg', style='width: 850px').m-auto
            .cajon.color-primario.p-4
              p.mb-0 Es importante señalar que para que exista dolo, la persona debe tener comprensión y decisión de la acción que se va a llevar a cabo, lo que en consecuencia origina un daño o perjuicio a otro ser humano; igualmente, el omitir una acción que va a causar daño o lesión a otro, se considera dolo. Esto quiere decir que el autor quería realizar la acción y que se generará una consecuencia en perjuicio del otro.
      div(titulo="Actitud")
        .row
          .col-12
            p Al referirnos a la actitud del primer respondiente, se debe recordar que las acciones del auxiliador deben ser enfocadas en dos aspectos: su autoprotección y prestar ayuda a quién lo necesita.
            p Según el Diccionario de la Lengua Española, la palabra actitud se puede definir como “disposición de ánimo manifestada de algún modo”.
            p Esto se puede interpretar como la disposición que tiene el auxiliador para ayudar a las personas que lo necesitan. 
            p.mb-5 La actitud posee factores que pueden interferir y modificar la naturaleza o la intención, tales como:
            figure.mb-5
              img(src='@/assets/curso/img12.svg', style='width: 950px').m-auto
            p Todas las acciones del primer respondiente deben enfocarse hacia la autoprotección, proteger a otros auxiliares, y ayudar al lesionado, para evitar al máximo secuelas, complicaciones, o lesiones posteriores.
            .row.align-items-center
              .col-lg-8
                .cajon.color-primario.p-4.mb-4
                  p.mb-0 Para entender y ejecutar acciones que no afecten la seguridad del auxiliador y la seguridad de la escena, y para brindar la correcta atención del lesionado, sin generar daños, es imperioso seguir las recomendaciones e instrucciones dadas por el profesional de la salud o persona experta, que se encuentre en la escena de la situación que generó el o los lesionados; no se trata de ser protagonista o dar la imagen de líder, lo importante realmente es prestar un servicio oportuno y pertinente.
                p.mb-5 Si se está preparado para desarrollar o fortalecer la buena actitud y las características de un buen auxiliador, es sustancial resaltar algunas características:
                ol.lista-ol--cuadro.ms-5
                  li
                    .lista-ol--cuadro__vineta
                      span a
                    | Autocontrol y conservar la calma.
                  li 
                    .lista-ol--cuadro__vineta
                      span b
                    | Consideración por la integridad y pudor del otro.
                  li 
                    .lista-ol--cuadro__vineta
                      span c
                    | Responsabilidad.
                  li 
                    .lista-ol--cuadro__vineta
                      span d
                    | Solidaridad.
                  li 
                    .lista-ol--cuadro__vineta
                      span e
                    | Imparcialidad.
              .col-lg-4
                figure
                  img(src='@/assets/curso/img13.svg', style='width: 450px').m-auto
      div(titulo="Autocontrol y conservar la calma")
        .row.align-items-center
          .col-4
            figure
              img(src='@/assets/curso/img14.svg', style='width: 300px').m-auto
          .col-8
            p.mb-0 Cuando el entorno engendra situaciones que no pueden ser controladas como, por ejemplo, una emergencia en la que se ha visto afectada la salud de una persona, o se presentan posibilidades de afectación, el instinto de supervivencia humano se activa y, en alguna oportunidad, las mismas acciones de los involucrados pueden llegar a ser instintivas, impidiendo identificar peligros del entorno y la situación real del lesionado (efecto túnel) El autocontrol contribuye a mantener la calma; esto quiere decir que durante una emergencia, en la cual se desea participar como auxiliador, antes de obrar, debe detenerse, pensar en cuáles son las acciones correctas a ejecutar y actuar con precaución.
      div(titulo="Respeto")
        .row
          .col-12
            p.mb-5 El respeto es advertido por el lesionado, por los familiares, por la autoridad y por todas las personas que se encuentran en el entorno. Durante una emergencia, algunas de las personas involucradas pueden presentar pánico; esto los llevará a sentirse extremadamente susceptibles hacia cualquier acción del entorno.
            figure
              img(src='@/assets/curso/img15.svg', style='width: 1250px').m-auto
      div(titulo="Responsabilidad")
        .row.align-items-center
          .col-8
            p El buen auxiliar deberá ser responsable de sus actos; por esta razón, debe comprometerse con la preparación continua y con el proceder respetuoso, no hacer daño al lesionado, no realizar acciones que desconoce y no experimentar desenlaces, debido a que esto afectará negativamente a la persona lesionada.
            p.mb-0 Es función importante del primer respondiente, portar los implementos básicos para auxiliar a un lesionado y autoprotegerse; además, estos instrumentos serán muy útiles en caso que el lesionado sea él.
          .col-4
            figure
              img(src='@/assets/curso/img16.svg', style='width: 300px').m-auto
      div(titulo="Solidaridad")
        .row
          .col-12
            p El buen auxiliar siempre procede sin esperar a cambio ningún beneficio; siempre actúa sin esperar un pago por su gesto de buena voluntad y constantemente actúa de manera humanitaria y neutral.
            .cajon.color-primario.p-4
              p.mb-0 En ninguna situación podrá solicitar pago por ayudar al lesionado, ni exigir que le devuelvan los implementos del botiquín, los cuales han sido utilizados y consumidos durante la ayuda.
      div(titulo="Principio de imparcialidad")
        .row.align-items-center.justify-content-end
          .col-lg-4.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/img17.svg', style='width: 300px').m-auto
          .col-lg-8
            p Debemos brindar apoyo a la persona lesionada, sin llevar a cabo ninguna clase de discriminación, ya sea por sexo, por raza, por origen nacional o familiar, lengua, religión, opinión política o filosófica.
            p La empatía y la buena actitud del primer respondiente, proporcionan y consolidan todos los propósitos de ayuda durante una situación de emergencia, al aumentar la interacción con el lesionado y los demás auxiliares o personas que están ubicadas como observadores. Tratar a los demás como usted desea que lo traten.
          .col-12
            .cajon.color-primario.p-4.mb-4
              .h5 ¿Piense que usted puede aprovechar los beneficios de una buena actitud, como primer respondiente? 
              p Si su respuesta es positiva y se encuentra dispuesto a brindar ayuda a quien lo necesite, de la misma forma que usted desea recibir, la invitación es para que se apropie del siguiente compromiso:
          .col-4
            a.anexo.mb-4(:href="obtenerLink('/downloads/anexo1.pdf')" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p #[b Anexo]. De compromiso
    separador.mb-5
    #t_1_3
    .titulo-segundo
      h2 1.3 Número único para emergencias
    p ¿Cuál es el número único para emergencias? La siguiente imagen lo ilustra.
    .row.align-items-center.justify-content-center.bg-color3.px-5
      .col-12.mb-5
        .row.align-items-start
          .col-lg-4.mb-5.mb-lg-0
            figure(data-aos="fade-left")
              img(src='@/assets/curso/img18.svg', style='width: 450px').m-auto
          .col-lg-8
            LineaTiempoD.color-primario
              .row(numero="1" titulo="Acceso")
                .col-12
                  p Se accede de forma gratuita las 24 horas del día, los 365 días del año.
              .row(numero="2" titulo="Número de emergencia")
                .col-12
                  p Es una línea única de emergencia nacional que agrupa todos los números de seguridad y emergencias de:
                  figure
                    img(src='@/assets/curso/img19.svg', style='width: 550px').m-auto
              .row(numero="3" titulo="Objetivo")
                .col-12
                  p Garantizar una respuesta adecuada, oportuna, efectiva y coordinada, en situaciones de urgencias, emergencias y desastres, desde las diferentes entidades que se encuentran incluidas en el sistema, para la prevención, atención y despacho de recursos físicos.
      .col-11
        .cajon.color-primario.p-4.mb-5
          p.mb-0 A través del Centro Regulador de Urgencia y Emergencias (CRUE) se coordina la atención prehospitalaria, servicio que se presta a la comunidad en general, y comprende los servicios de salvamento, atención médica y transporte, a enfermos o accidentados en el sitio del incidente.
      .col-12
        .h4 ¿Cuándo solicitar el servicio de atención prehospitalaria?
        p.mb-5 El servicio de atención prehospitalaria se debe solicitar a través de la línea 123, cuando se presente alguna de las siguientes situaciones:
        .row.align-items-center.mb-5
          .col-lg-6
            ul.lista-ul.ms-5
              li 
                i.fas.fa-atom(style="color: #00BCD4")
                | Accidente de tránsito con heridos o lesionados.
              li 
                i.fas.fa-atom(style="color: #00BCD4")
                | Persona herida en la vía pública.
              li 
                i.fas.fa-atom(style="color: #00BCD4")
                | Dolor en el tórax o en el pecho y que no cede con el reposo.
              li 
                i.fas.fa-atom(style="color: #00BCD4")
                | Madre gestante de alto riesgo.
              li 
                i.fas.fa-atom(style="color: #00BCD4")
                | Embarazos con trabajo de parto en curso.
              li 
                i.fas.fa-atom(style="color: #00BCD4")
                | Intoxicación.
              li 
                i.fas.fa-atom(style="color: #00BCD4")
                | Caída desde una altura considerable.
              li 
                i.fas.fa-atom(style="color: #00BCD4")
                | Persona inconsciente.
              li 
                i.fas.fa-atom(style="color: #00BCD4")
                | Persona que no respira o que tiene dificultad para respirar.
              li 
                i.fas.fa-atom(style="color: #00BCD4")
                | Persona con alteraciones en su comportamiento mental.
              li 
                i.fas.fa-atom(style="color: #00BCD4")
                | Herido por arma blanca.
              li 
                i.fas.fa-atom(style="color: #00BCD4")
                | Herido por arma de fuego.
          .col-lg-6
            figure(data-aos="fade-right")
              img(src='@/assets/curso/img3.png', style='width: 270px').m-auto
        .cajon.color-primario.p-4
          p.mb-0 Es importante recordar que la prioridad de atención, de esta línea, son las urgencias críticas. Una vida humana puede depender de una llamada telefónica, por lo tanto es importante no congestionar la línea 123 con llamadas innecesarias. En el mismo lugar del evento y mientras llega el equipo especializado, iniciar la primera ayuda: activar la línea de emergencia, tener toda la información posible de manera inmediata y seguir las instrucciones telefónicas del equipo de salud.
    separador.mb-5
    #t_1_4
    .titulo-segundo
      h2 1.4 Principios básicos de la actuación del primer respondiente
    p.mb-5 Teniendo en cuenta lo estudiado anteriormente, analicemos cuáles son los principios básicos de la actuación del primer respondiente, a través de la siguiente imagen.
    .h5.mb-5 Actuación primer respondiente
    .row
      .col-12
        LineaTiempoC.color-acento-contenido
          .row(titulo="1")
            .col-12
              figure
                img(src='@/assets/curso/img56.svg', style="width:1000px").m-auto
          .row(titulo="2")
            .col-12
              figure
                img(src='@/assets/curso/img57.svg', style="width:1000px").m-auto
          .row(titulo="3")
            .col-12
              figure
                img(src='@/assets/curso/img58.svg', style="width:1000px").m-auto
          .row(titulo="4")
            .col-12
              figure
                img(src='@/assets/curso/img59.svg', style="width:1000px").m-auto
          .row(titulo="5")
            .col-12
              figure
                img(src='@/assets/curso/img60.svg', style="width:1000px").m-auto
          .row(titulo="6")
            .col-12
              figure
                img(src='@/assets/curso/img61.svg', style="width:1000px").m-auto
          .row(titulo="7")
            .col-12
              figure
                img(src='@/assets/curso/img62.svg', style="width:1000px").m-auto
          .row(titulo="8")
            .col-12
              figure
                img(src='@/assets/curso/img63.svg', style="width:1000px").m-auto
          .row(titulo="9")
            .col-12
              figure
                img(src='@/assets/curso/img64.svg', style="width:1000px").m-auto
          .row(titulo="10")
            .col-12
              figure
                img(src='@/assets/curso/img65.svg', style="width:1000px").m-auto
          .row(titulo="11")
            .col-12
              figure
                img(src='@/assets/curso/img66.svg', style="width:1000px").m-auto
          
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
