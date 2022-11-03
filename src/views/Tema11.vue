<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos="fade-down-right")
      .titulo-principal__numero.text-white
        span 11
      h1 Tratamiento y disposición de residuos de laboratorio
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema11/imagen1.jpg')})`}"
      )
      .bloque-texto-g__texto.px-4.py-5
        p Se abordarán las características de tratamiento y disposición de los residuos generados en el laboratorio; estos, son los productos químicos que quedan en pequeñas cantidades como restos inutilizables y son residuos especiales ya que pueden ser residuos de disolventes orgánicos halogenados y no halogenados, compuestos mercuriados, ácidos orgánicos e inorgánicos, bases, sales y demás compuestos que se hallen en el laboratorio.
    .row.justify-content-center.my-5
      .col-lg-8.col-md-10.col-sm-12(data-aos="fade-down-right")
        .row.justify-content-center.align-items-center.fondo-5.ps-3.pe-5.py-4.redondearpuntas.mb-4
          .col-md-2.col-sm-3.col-4
            img(src='@/assets/curso/tema4/descargar-pdf.svg')
          .col-xxl-8.col-md-7.text-white
            h3.mb-0 Tratamiento y disposición residuos
            p.text-small.mb-4.mb-md-0 Para profundizar en el tema
              span.text-bold “tratamiento y disposición de los residuos generados en el laboratorio”
              span , le invitamos a estudiar con atención este documento. 
          .col-xxl-2.col-md-3
            a.boton.color-acento-botones(:href="obtenerLink('downloads/Tratamiento_y_disposicion_de_los_residuos_generados_en_el_laboratorio.pdf')" target="_blank" type="application/pdf")
              span Descargar
              i.fas.fa-file-download
</template>

<script>
export default {
  name: 'Tema11',
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
