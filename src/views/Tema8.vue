<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos="fade-down-right")
      .titulo-principal__numero.text-white
        span 8
      h1 Equipos para análisis de suelos
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema8/imagen1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4.py-5
        p La calidad del suelo ha sido definida por la Sociedad de Ciencias del Suelo de América como “la capacidad de un tipo específico de suelo para funcionar, dentro de los límites de los ecosistemas naturales, para sostener la productividad vegetal y animal, mantener y/o mejorar la calidad del agua y del aire, y apoyar la salud y la vivienda”.
    p.my-5(data-aos="fade-down") Esta funcionalidad del suelo varía dependiendo del interés del observador: para los administradores puede significar la capacidad del suelo de mejorar la productividad y mantener los recursos del suelo para el futuro; para los conservacionistas mantener los recursos del suelo y la protección del medio ambiente; para los consumidores la producción de alimentos sanos y de bajo costo; para los ambientalistas la capacidad de sustentar la biodiversidad, la calidad del agua, el ciclo de nutrientes y la producción de biomasa. 
    .row.justify-content-center
      .col-lg-6.col-md-12(data-aos="fade-down-right")
        p De acuerdo a Gómez J.C (2013):
        p La calidad del suelo, entonces, es cada vez más aceptada como un indicador integral de la calidad ambiental, seguridad alimentaria y viabilidad económica. 
        p Por lo tanto, es un indicador ideal de la gestión sostenible de la tierra.
        p Es así, que se hace indispensable conocer en qué estado y que tan funcional es un suelo para tomar las decisiones pertinentes de uso y manejo; de esta manera el análisis de suelos entra a jugar un papel importantísimo en los diagnósticos de calidad ya que es éste el que nos va a permitir reconocer de manera puntual cada una de las características físicas y químicas. (pp 51-52).
      .col-lg-6.col-md-12(data-aos="fade-down-left")
        img(src='@/assets/curso/tema8/imagen2.jpg')
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
            a.boton.color-acento-botones(:href="obtenerLink('downloads/Tabla_9_Equipos_utilizados_en_los_analisis_del_suelo.pdf')" target="_blank" type="application/pdf")
              span Descargar
              i.fas.fa-file-download
</template>

<script>
export default {
  name: 'Tema8',
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
