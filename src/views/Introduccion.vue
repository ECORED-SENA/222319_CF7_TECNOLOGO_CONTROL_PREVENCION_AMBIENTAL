<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido.mb-0(data-aos="fade-down-right")
      .titulo-principal__numero.text-white
        span
          i.fas.fa-info
      h1 Introducción
    .row.fondo-1.py-5.mt-0
      .col-12
        .row.justify-content-center
          .col-lg-10.col-md-12.mb-5(data-aos="fade-down-right")
            p.text-center La importancia del análisis de las muestras que se llevan al laboratorio radica particularmente en el tratamiento que se le de a las mismas, desde la toma, el embalaje, el transporte y su respectiva identificación.
            p.text-center Puesto que, si las muestras son alteradas en alguno de los procesos de la muestra, su posterior análisis entra en un margen de baja confiabilidad que se traduce en un resultado de poca fiabilidad.
          .col-lg-6.col-md-8.col-sm-10.col-12.mt-5(data-aos="fade-down-left")
            img(src='@/assets/curso/intro/figura.png')
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
