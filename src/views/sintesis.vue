<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p.mb-5 Por último, el siguiente mapa conceptual aborda la importancia de implementar el sistema de emergencias médicas en Colombia, brindando asistencia según protocolo de primer respondiente y normativas de salud, asegurando el escenario de emergencia con base en la situación, recursos y protocolos establecidos. Sabiendo esto y para una breve revisión de los temas vistos, puede observar el siguiente esquema:

    .row.justify-content-center
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="El esquema representa la síntesis del componente formativo, Sistema de emergencias médicas colombianas, teniendo en cuenta qué permite, qué establece la normativa y facilita, quién verifica, que procesos se garantizan , qué se analiza y cómo se recopilan los datos, dando explicación de cada uno de estos.")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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

<style lang="sass"></style>
