<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos="fade-down-right")
      .titulo-principal__numero.text-white
        span 1
      h1 Aplicación de protocolos de análisis de muestras
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/imagen1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Dentro de la química analítica, se incluye el análisis químico que es la parte práctica que aplica los métodos de análisis para resolver problemas relativos a la composición y naturaleza química de la materia. Los ámbitos de aplicación del análisis químico son muy variados, en la industria destaca el control de calidad de materias primas y productos terminados; en los laboratorios certificados de análisis quienes aseguran las especificaciones de calidad de las mercaderías; en el campo de la medicina, los análisis clínicos facilitan el diagnóstico de enfermedades entre otros.

    .row.justify-content-center.my-5(data-aos="fade-left")
      .col-lg-10.position-relative
        .avatar
          figure
            img(src="@/assets/curso/tema1/imagen2.svg", alt="alt").img530
        .crd.crd--avatarHorizontal.crd--first.py-4
          .row.align-items-center
            .col-auto
              figure
                img(src="@/assets/curso/tema1/figura1.svg", alt="alt").img100
            .col
              h5 Por esta razón:
              p En esta unidad temática, se profundiza como se desarrolla en el análisis de las muestras que se lleva a cabo en el laboratorio. La química analítica es la rama de la química que tiene como finalidad el estudio de la composición química de un material o muestra, mediante diferentes métodos. Se divide en química analítica cuantitativa y química analítica cualitativa.
        .crd.crd--avatarHorizontal.py-4
          .row.align-items-center
            .col-auto
              figure
                img(src="@/assets/curso/tema1/figura2.svg", alt="alt").img100
            .col
              h5 Dentro de la química analítica:
              p Se incluye el análisis químico que es la parte práctica que aplica los métodos de análisis para resolver problemas relativos a la composición y naturaleza química de la materia.
        .crd.crd--avatarHorizontal.crd--last.py-4
          .row.align-items-center
            .col-auto
              figure
                img(src="@/assets/curso/tema1/figura3.svg", alt="alt").img100
            .col
              h5 Los ámbitos de aplicación:
              p Del análisis químico son muy variados, en la industria se destaca el control de calidad de materias primas y productos terminados; en los laboratorios certificados de análisis quienes aseguran las especificaciones de calidad de las mercaderías; en el campo de la medicina, los análisis clínicos facilitan el diagnóstico de enfermedades.




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

<style lang="sass"></style>
