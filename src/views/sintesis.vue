<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p.mb-5 El siguiente diagrama está organizado en tres secciones principales: análisis y planificación, diseño de infraestructura, e implementación de redes físicas. Cada sección contiene subcategorías que detallan los componentes y procesos involucrados, lo cual permite hacer relaciones entre las diferentes fases y componentes del diseño e implementación de redes. Esto facilita la comprensión visual de la información.
    p.mb-5 Para comprender los elementos clave de este diagrama, el aprendiz puede analizar cómo las diferentes fases y componentes están interrelacionados. Por ejemplo, la sección de diseño de infraestructura está conectada con la sección de implementación de redes físicas, mostrando cómo la planificación y el diseño adecuados son necesarios para una implementación exitosa.
    p.mb-5 Este diagrama proporciona una representación visual clara y organizada de los componentes y procesos involucrados en el diseño e implementación de redes, facilitando la comprensión y el uso de la información.

    .row.justify-content-center
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="La Figura 2 se denomina «Síntesis temática del componente», allí se mencionan los principales temas tratados sobre el diseño e implementación de redes como el análisis y planificación, el diseño e infraestructura, la implementación de redes físicas y algunos subtemas que los integran.")
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
