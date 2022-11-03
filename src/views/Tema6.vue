<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos="fade-down-right")
      .titulo-principal__numero.text-white
        span 6
      h1 Equipos de análisis de agua
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema6/imagen1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p Las técnicas instrumentales de análisis tienen gran relevancia en el monitoreo de la calidad del agua, como también durante el proceso de tratamiento de agua residual. La concentración de metales y aniones en el agua se pueden detectar, empleando técnicas modernas de análisis.
        br
        br
        p Es de gran importancia hallar las concentraciones de estos componentes para tener un conocimiento de su calidad y corroborar si se cumple con los límites máximos permisibles nacionales e internacionales.
    .row.justify-content-center.my-5
      .col-lg-8.col-md-10.col-sm-12(data-aos="fade-down-right")
        .row.justify-content-center.align-items-center.fondo-5.ps-3.pe-5.py-4.redondearpuntas.mb-4
          .col-md-2.col-sm-3.col-4
            img(src='@/assets/curso/tema4/descargar-pdf.svg')
          .col-xxl-8.col-md-7.text-white
            h3.mb-0 Equipos utilizados en los análisis de agua
            p.text-small.mb-4.mb-md-0 Visita la tabla 7 en el anexo 8 donde se muestran algunos equipos utilizados en los análisis de agua.
          .col-xxl-2.col-md-3
            a.boton.color-acento-botones(:href="obtenerLink('downloads/Tabla_7_Equipos_instrumentales_de_analisis.pdf')" target="_blank" type="application/pdf")
              span Descargar
              i.fas.fa-file-download
</template>

<script>
export default {
  name: 'Tema6',
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
