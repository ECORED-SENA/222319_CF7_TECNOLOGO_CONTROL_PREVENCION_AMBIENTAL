<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos="fade-down-right")
      .titulo-principal__numero.text-white
        span 9
      h1 Protocolo para análisis de olores
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema9/imagen1.jpg')})`}"
      )
      .bloque-texto-g__texto.px-4.py-5
        p La olfatometría es una técnica de toma de muestras y análisis de olores, que unida al desarrollo de sistemas de modelización de la dispersión, permite evaluar las molestias producidas por malos olores y determinar el origen de las mismas. Los estudios olfatométricos constituyen una herramienta de gran utilidad para el control y reducción de los malos olores emitidos por distintos tipos de fuentes.
    .row.justify-content-center.my-5
      .col-lg-8.col-md-10.col-sm-12(data-aos="fade-down-right")
        .row.justify-content-center.align-items-center.fondo-5.ps-3.pe-5.py-4.redondearpuntas.mb-4
          .col-md-2.col-sm-3.col-4
            img(src='@/assets/curso/tema4/descargar-pdf.svg')
          .col-xxl-8.col-md-7.text-white
            h3.mb-0 Protocolo para análisis de olores
            p.text-small.mb-4.mb-md-0 Para profundizar en el tema 
              span.text-bold “Protocolo para análisis de olores”
              span , le invitamos a estudiar con atención este documento. 
          .col-xxl-2.col-md-3
            a.boton.color-acento-botones(:href="obtenerLink('downloads/Protocolo_para_analisis_de_olores.pdf')" target="_blank" type="application/pdf")
              span Descargar
              i.fas.fa-file-download
</template>

<script>
export default {
  name: 'Tema9',
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
