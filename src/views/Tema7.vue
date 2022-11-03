<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos="fade-down-right")
      .titulo-principal__numero.text-white
        span 7
      h1 Protocolos de análisis de suelos
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema7/imagen1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4.py-5
        p Según Fernández L.C (2006):
        br
        br
        p El suelo es un cuerpo natural que conforma el hábitat de bacterias, hongos, levaduras, virus y plantas superiores, entre otros, que sirve para la alimentación de los animales y del hombre a través de los ciclos tróficos.
    .row.justify-content-between.mt-5
      .col-lg-4.col-md-6.col-sm-12(data-aos="fade-down-right")
        .tarjeta-avatar
          img.p-4(src='@/assets/curso/tema7/icono1.svg')
          .tarjeta.fondo-12
            .text-dark.p-4.pt-2
              p.text-center El suelo y los microorganismos mantienen los sistemas ecológicos, ya que le aportan componentes químicos y minerales (como resultado de la biodegradación) y complejos orgánicos como ácidos húmicos y fúlvicos, enzimas, vitaminas, hormonas y antibióticos; además, albergan una rica reserva genética.
      .col-lg-4.col-md-6.col-sm-12(data-aos="fade-down")
        .tarjeta-avatar
          img.p-4(src='@/assets/curso/tema7/icono2.svg')
          .tarjeta.fondo-12
            .text-dark.p-4.pt-2
              p.text-center Por la gran importancia que representa el suelo para la vida del hombre y de todos los seres vivos, este recurso se debe conservar. Sin embargo, en la actualidad está seriamente amenazado por la práctica de sistemas de producción inadecuados o mal aplicados, que incluso han acelerado los procesos de erosión y desertificación de grandes zonas.
      .col-lg-4.col-md-6.col-sm-12(data-aos="fade-down-left")
        .tarjeta-avatar
          img.p-4(src='@/assets/curso/tema7/icono3.svg')
          .tarjeta.fondo-12
            .text-dark.p-4.pt-2
              p.text-center De igual forma, la industrialización y urbanización han generado una gran cantidad de desechos que son incorporados al suelo, lo cual ocasiona tanto la reducción de su fertilidad como la modificación de sus procesos naturales. Por lo anterior, es necesario estudiar las características particulares del suelo para determinar su grado de contaminación y, consecuentemente, aplicar alguna de las tecnologías de remediación existentes. (p.13).
    .row.justify-content-center.my-5
      .col-lg-8.col-md-10.col-sm-12(data-aos="fade-down-right")
        .row.justify-content-center.align-items-center.fondo-5.ps-3.pe-5.py-4.redondearpuntas.mb-4
          .col-md-2.col-sm-3.col-4
            img(src='@/assets/curso/tema4/descargar-pdf.svg')
          .col-xxl-8.col-md-7.text-white
            h3.mb-0 Protocolo de análisis de suelos
            p.text-small.mb-4.mb-md-0 Para profundizar en el tema 
              span.text-bold “Protocolo de análisis de suelos”
              span , le invitamos a estudiar con atención este documento. 
          .col-xxl-2.col-md-3
            a.boton.color-acento-botones(:href="obtenerLink('downloads/Protocolo_de_analisis_de_suelos.pdf')" target="_blank" type="application/pdf")
              span Descargar
              i.fas.fa-file-download
</template>

<script>
export default {
  name: 'Tema7',
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
