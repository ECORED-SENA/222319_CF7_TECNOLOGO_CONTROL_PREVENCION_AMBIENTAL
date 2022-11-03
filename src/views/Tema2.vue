<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos="fade-down-right")
      .titulo-principal__numero.text-white
        span 2
      h1 Inducción al análisis de muestras
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2/imagen1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0.mb-3 La 
          span.text-bold química analítica 
          span es el estudio de cómo ensayar esos materiales para averiguar su composición elemental y molecular.
        p.mb-0 El poder determinar la composición química de sólidos, líquidos, gases, disoluciones y cualquier otro material nos permite comprender sus características y así poder evaluar sus usos o quizás descubrir de dónde vinieron o dónde han estado.
    p.my-5(data-aos="fade-down-left") A continuación, le presentamos algunos elementos de orden teórico que favorecen la “inmersión” en el tema del 
      span.text-bold análisis de muestras.
    .row.justify-content-center
      .col-lg-6.col-md-8.col-sm-10.col-12(data-aos="fade-down-right")
        ImagenInfograficaB.color-primario.mb-5
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/tema2/figura1.svg')

          div(x="50%" y="15%" tooltip="De click para leer mas...")
            .row.justify-content-center
              .col-lg-7.col-md-12
                h5 ¿De qué se trata?
                p La química analítica trata de la separación y caracterización de sustancias químicas que hacen parte de una muestra que bien puede ser considerada como contaminada por estas sustancias o que es importante determinar su presencia por razones de interés económico o toxicológico.
                p Casi siempre en el análisis químico se trata de encontrar la composición de la muestra y la estructura química de los componentes mediante sus métodos de análisis.
              .col-lg-4.col-md-10
                img(src='@/assets/curso/tema2/imagen3.png')

          div(x="32%" y="51%" tooltip="De click para leer mas...")
            .row.justify-content-center
              .col-lg-7.col-md-12
                .h5.mb-2 Ciencia creadora
                p Mientras el análisis químico es técnico, la química analítica es ciencia creadora y elaboradora de dicha técnica, para lo cual establece leyes y principios que justifican el por qué y el cómo de los procesos.
                p Divisiones del análisis químico. El análisis químico se divide en:
                ul.lista-ul
                  li 
                    i.fas.fa-check
                    | Análisis químico cualitativo: tiene por objeto el reconocimiento o identificación de los elementos o de los grupos químicos presentes en una muestra. Las operaciones que se realizan son muy sencillas, entre las que podemos mencionar disolución de la muestra en un solvente adecuado, separación de impurezas, ya sea por decantación, filtración o centrifugación. El material que se requiere consiste en tubos de ensayos, vasos de precipitados, probetas, cápsulas de porcelana, papel de filtro.
                  li 
                    i.fas.fa-check
                    | Análisis químico cuantitativo: determina las cantidades de los elementos y compuestos que componen una muestra y sus posibles relaciones químicas e incluso estructurales.
              .col-lg-4.col-md-10
                img(src='@/assets/curso/tema2/imagen5.png')

          div(x="83%" y="57.5%" tooltip="De click para leer mas...")
            .row.justify-content-center
              .col-lg-7.col-md-12
                h5 Química analítica
                p La química analítica no solo nos permite resolver problemas específicos sino también descubrir mejores métodos para conseguirlo. La química analítica se ocupa de la separación, identificación y determinación de la composición relativa de una muestra de materia.
                p El análisis cualitativo identifica químicamente a las especies que hay en la muestra. El análisis cuantitativo establece la cantidad relativa de una o más de estas especies, o analitos, en términos numéricos.
                p Para poder realizar el análisis cuantitativo es necesario contar primero con información cualitativa. Tanto el análisis cualitativo como el cuantitativo precisan de una fase de separación.
              .col-lg-4.col-md-10
                img(src='@/assets/curso/tema2/imagen2.png')
          div(x="32%" y="87%" tooltip="De click para leer mas...")
            .row.justify-content-center
              .col-lg-7.col-md-12
                .h5.mb-2 Los métodos
                p Los métodos analíticos que dependen de la cantidad de muestra tomada pueden ser clasificados en:
                ul.lista-ul
                  li 
                    i.fas.fa-check
                    | Macroanálisis: sí la cantidad de muestra está comprendida aproximadamente entre 0.1 - 2 g.
                  li 
                    i.fas.fa-check
                    | Semimicroanálisis: cantidad comprendida aproximadamente entre 0.01 a 0.05 g (10 a 50 mg).
                  li 
                    i.fas.fa-check
                    | Microanálisis: de 1 a unos pocos miligramos (0.001g).
                  li 
                    i.fas.fa-check
                    | Ultra Microanálisis: Determina una cantidad de material del orden de unos cuantos miligramos (0.001 mg = 1 g).
              .col-lg-4.col-md-10
                img(src='@/assets/curso/tema2/imagen4.png')
          div(x="83%" y="87%" tooltip="De click para leer mas...")
            .row.justify-content-center
              .col-lg-7.col-md-12
                .h5.mb-2 Reacciones
                p La base en la que se fundamentan la mayoría de los procesos químicos analíticos son las reacciones químicas.
              .col-lg-4.col-md-10
                img(src='@/assets/curso/tema2/imagen6.png')
</template>

<script>
export default {
  name: 'Tema2',
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
