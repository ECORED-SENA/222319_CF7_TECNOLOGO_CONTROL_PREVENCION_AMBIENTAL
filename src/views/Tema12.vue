<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos="fade-down-right")
      .titulo-principal__numero.text-white
        span 12
      h1 Análisis de datos
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema12/imagen1.jpg')})`}"
      )
      .bloque-texto-g__texto.px-4.py-5
        p  Los análisis fisicoquímicos y microbiológicos de las muestras ambientales (agua, suelo, aire y residuos sólidos) comprenden la separación, identificación y determinación de las cantidades relativas de los componentes de una muestra; es decir es un análisis cuantitativo que determina ¿cuánto? de determinado componente está presente en la muestra analizada. El resultado numérico tendrá significado dentro del contexto del análisis, por tanto, es necesario realizar un tratamiento matemático que lleve al valor que mejor represente el resultado buscado.
    separador
    #t_12_1.titulo-segundo.color-acento-contenido(data-aos="fade-down-right")
      h2 12.1 Las cifras significativas
    p(data-aos="fade-down-right") Las cifras significativas de una medida indican, implícitamente, la incertidumbre o inexactitud de la medida sin necesidad de incluir el símbolo “±”. El reporte debe contener un solo dígito incierto o inexacto: el último, que corresponde a la apreciación del instrumento.
    p(data-aos="fade-down-right") “Las cifras significativas son los dígitos significativos en una cantidad medida o calculada”) y se sobreentiende que el último dígito es incierto o inexacto. En el caso mostrado en la siguiente imagen, con la pipeta A (4 mL) se está reportando una sola cifra significativa; con la pipeta B (4,0 mL) se están reportando dos cifras significativas.
    .row.justify-content-center.my-5
      .col-lg-8.col-md-12.fondo-17.p-5(data-aos="fade-down-right")
        .row.justify-content-center
          .col-sm-5.col-10.order-0.order-sm-0
            img.order-0(src='@/assets/curso/tema12/pipeta_a.svg')
          .col-sm-5.col-10.order-2.order-sm-1
            img(src='@/assets/curso/tema12/pipeta_b.svg')

          .col-sm-5.col-10.order-1.order-sm-2.mb-3
            p.mb-0.text-center.text-bold Pipeta A
            p.text-center.order-last Volumen: 4 mL  ± 1 mL
          .col-sm-5.col-10.order-3.order-sm-3.mb-3
            p.mb-0.text-center.text-bold Pipeta B
            p.text-center Volumen: 4,0 mL  ± 1 mL
    separador
    #t_12_2.titulo-segundo.color-acento-contenido(data-aos="fade-down-right")
      h2 12.2 Reglas para utilizar cifras significativas
    p.mb-5(data-aos="fade-down-right") A continuación, le presentamos una serie de reglas que le permitirán utilizar cifras significativas.

    .row.justify-content-center.my-5(data-aos="fade-left")
      .col-lg-10.position-relative
        .avatar
          figure
            img(src="@/assets/curso/tema12/figura1.svg").img450
        .crd.crd--avatarHorizontal.crd--first.py-4
          .row.align-items-center
            .col-auto
              figure
                img(src="@/assets/curso/tema12/numero-uno.svg", alt="alt").img100
            .col
              h5 Todo dígito diferente de cero es una cifra significativa:
              p 6 mL tiene una sola cifra significativa. 6,0 mL tiene dos cifras significativas; 640 mL tiene tres cifras significativas.
        .crd.crd--avatarHorizontal.py-4
          .row.align-items-center
            .col-auto
              figure
                img(src="@/assets/curso/tema12/numero-2.svg", alt="alt").img100
            .col
              h5 Todo cero que se encuentre entre dos dígitos diferentes de cero, es una cifra significativa: 
              p 307 g tiene tres cifras significativas; 5024 mL tiene cuatro cifras significativas.
        .crd.crd--avatarHorizontal.crd--last.py-4
          .row.align-items-center
            .col-auto
              figure
                img(src="@/assets/curso/tema12/numero-3.svg", alt="alt").img100
            .col
              h5 Los ceros a la izquierda del primer dígito diferente de cero no son cifras significativas:
              p 0,305 kg tiene tres cifras significativas; 0,0085 L tiene dos cifras significativas; 0,00003204 km tiene cuatro cifras significativas; 0,05 cm3 tiene una sola cifra significativa.
    p.my-5(data-aos="fade-down-right") Una forma sencilla de diferenciar cuales ceros son cifras significativas, es cambiar de notación decimal a notación científica ya que las cifras significativas se mantienen sin importar la notación.
    .row.justify-content-center
      .col-lg-8.col-md-8.col-sm-10.col-12
        .tabla-c(data-aos="fade-down-right")
          //-.div.table-responsive
          table
            tr
              td.fondo-9.text-center.borde-der.borde-izq
                .h4 Notación Decimal
              td.fondo-9.text-center.borde-der
                .h4 Notación Científica
              td.fondo-9.text-center.borde-der
                .h4 Cifras significativas
            tr
              td.text-center.borde-der.borde-izq 0,305
              td.text-center.borde-der = 3,05 x 10─1
              td.text-center.borde-der Tiene tres cifras significativas
            tr
              td.text-center.borde-der.borde-izq 0,0086
              td.text-center.borde-der = 8,6 x 10─3
              td.text-center.borde-der Tiene dos cifras significativas
            tr
              td.text-center.borde-der.borde-izq 0,00001004
              td.text-center.borde-der = 1,004 x 10─5
              td.text-center.borde-der.p-0.m-0 Tiene cuatro cifras significativas
            tr
              td.text-center.borde-der.borde-abajo.borde-izq 0,03
              td.text-center.borde-der.borde-abajo = 3 x 10─2
              td.text-center.borde-der.borde-abajo Tiene una sola cifra significativa
    p.my-5(data-aos="fade-down-right") De acuerdo a Luzardo M (2016):
    .row.justify-content-center.my-5(data-aos="fade-left")
      .col-lg-10.position-relative
        .avatar
          figure
            img(src="@/assets/curso/tema12/figura2.svg").img600
        .crd.crd--avatarHorizontal.crd--first.py-4
          .row.align-items-center
            .col-auto
              figure
                img(src="@/assets/curso/tema12/numero-uno.svg", alt="alt").img100
            .col
              h5 Todos los ceros a la derecha de una cifra diferente de cero son cifras significativas. 
              p -   2,00 m tiene tres cifras significativas
              p -   3,2400 L tiene cinco cifras significativas.
              p -   120 L tiene tres cifras significativas
              p.mb-3 -   200 g tiene tres cifras significativas
              p 25000 mL tiene cinco cifras significativas si se midió con un instrumento cuya apreciación es 1 mL, pero sólo tendrá tres cifras significativas si la apreciación es 100 mL.
        .crd.crd--avatarHorizontal.py-4.crd--2
          .row.align-items-center
            .col-auto
              figure
                img(src="@/assets/curso/tema12/numero-2.svg", alt="alt").img100
            .col
              h5 Cuando se desee expresar una cantidad sin que queden dudas, es recomendable usar la notación científica:
              p -   120 L con sólo dos cifras significativas se expresará 1,2 x 102 L.
              p -   25000 mL con tres cifras significativas se expresará 2,50 x 104 mL.
        .crd.crd--avatarHorizontal.py-4.crd--3
          .row.align-items-center
            .col-auto
              figure
                img(src="@/assets/curso/tema12/numero-3.svg", alt="alt").img100
            .col
              h5 Cuando se resuelven problemas, las cifras significativas deberán indicarse en el enunciado.
              p En caso de duda se recomienda al estudiante utilizar al menos tres cifras. significativas en todos los cálculos.
        .crd.crd--avatarHorizontal.crd--4.py-4
          .row.align-items-center
            .col-auto
              figure
                img(src="@/assets/curso/tema12/numero-4.svg", alt="alt").img100
            .col
              h5 Cuando se resuelven problemas que implican datos experimentales, se deben tomar las cifras significativas que indique el instrumento de medida. (p.24)
    separador
    #t_12_3.titulo-segundo.color-acento-contenido(data-aos="fade-down-right")
      h2 12.3 Exactitud y precisión
    p.mb-5(data-aos="fade-down-right") Cuando se analizan los datos obtenidos en un análisis es importante tomar en cuenta la exactitud y la precisión de los valores obtenidos experimentalmente.
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema12/imagen2.jpg')})`}"
      )
      .bloque-texto-g__texto.px-4.py-5
        p Se denomina 
          span.text-bold exactitud 
          span a la cercanía de un resultado al valor considerado como verdadero. Una medida será más exacta mientras más cerca del valor verdadero se encuentre. Para determinar la exactitud de un resultado es necesario conocer previamente el valor verdadero (valor real) de la medida.Se denomina precisión de un grupo de medidas a la dispersión o separación de las mismas. Un grupo de medidas tendrá mayor precisión cuanto más cercanas se encuentren unas de otras. Se puede determinar la precisión sin necesidad de conocer el valor verdadero o real.
    .row.justify-content-center.my-5
      .col-lg-10.col-md-12(data-aos="fade-down-right")
        .cajon.color-acento-contenido.otrocolor.p-4.mb-4
          .row.justify-content-center.align-items-center
            .col-lg-1.col-md-2.col-sm-2.col-3.mb-4.mb-sm-0
              img(src='@/assets/curso/tema12/figura3.svg')
            .col-lg-11.col-md-10.col-sm-10.col-12
              p.mb-0 La exactitud y la precisión no son dependientes entre sí: puede existir precisión sin exactitud y viceversa.
    p.mb-5(data-aos="fade-down-right") Para comprender mejor estos términos, se utilizará como ejemplo una “diana” de tiro al blanco. El valor considerado como valor real o valor verdadero es el centro de la diana y los puntos corresponden a los lanzamientos realizados que equivaldrían a los resultados de los análisis.
    .row.justify-content-center
      .col-lg-8.col-md-10.col-sm-12
        //-.tabla-c(data-aos="fade-down-right")
        .titulo-sexto.color-acento-contenido(data-aos="fade-down")
          h5 Tabla 3. 
          span Exactitud y precisión
        .tabla-c(data-aos="fade-down-right")
          //-.div.table-responsive
          table
            caption.fuente-size.fondogris.fuente-regular Nota.Luzardo M. (s, f) Exactitud y precisión
            tr
              td.fondo-9.borde-der.borde-izq
                img(src='@/assets/curso/tema12/fig4.svg')
              td.fondo-9.borde-der
                img(src='@/assets/curso/tema12/fig5.svg')
              td.fondo-9.borde-der
                img(src='@/assets/curso/tema12/fig6.svg')
              td.fondo-9.borde-der
                img(src='@/assets/curso/tema12/fig7.svg')
            tr.fondogris
              td.borde-der.borde-izq.fuente-size 1- Precisos, pero no exactos (cercanos entre sí, pero desviados del centro).
              td.borde-der.fuente-size 2- Exactos, pero no precisos (cercanos al centro, pero alejados entre sí).
              td.borde-der.fuente-size 3- Ni precisos ni exactos.
              td.borde-der.fuente-size 4- Precisos y exactos (cercanos entre sí y todos cerca del centro).
    separador
    #t_12_4.titulo-segundo.color-acento-contenido(data-aos="fade-down-right")
      h2 12.4 Tratamiento matemático de los datos
    p(data-aos="fade-down-right") En el siguiente ejercicio se muestra el tratamiento matemático de un análisis de una muestra de agua, en el cual se obtienen una serie de valores que deben ser estudiados y sometidos a un tratamiento estadístico, a fin de reportar un único resultado.
    p.mb-5(data-aos="fade-down-right") En un laboratorio de análisis ambientales, tecnología en prevención y control ambiental del SENA, se desea determinar el contenido de hierro en el agua de una laguna, para lo cual se toman diez muestras y se analizan en el laboratorio. Un laboratorio externo de control de carácter oficial reporta que el contenido de cloro en la laguna es de 250,0 mg/L de Cl. Del análisis se obtuvieron los siguientes resultados:
    .row.justify-content-center
      .col-lg-8.col-md-10.col-sm-12
        .titulo-sexto.color-acento-contenido(data-aos="fade-down")
          h5 Tabla 4. 
          span Tratamiento matemático de los datos
        .tabla-c(data-aos="fade-down-right")
          //-.div.table-responsive
          table
            tr
              td.fondo-9.anchocol3.text-center.borde-der.borde-izq
                .h4 No. de la muestra
              td.fondo-9.anchocol3.text-center.borde-der
                .h4 Contenido de Cl (mg)/L
              td.fondo-9.anchocol3.text-center.borde-der
                .h4 No. de la muestra
              td.fondo-9.anchocol3.text-center.borde-der
                .h4 Contenido de Cl (mg)/L
            tr.fondogris
              td.anchocol2.text-center.borde-der.borde-izq 1
              td.anchocol2.text-center.borde-der 224,3
              td.anchocol3.text-center.borde-der 6
              td.anchocol3.text-center.borde-der 261,7
            tr
              td.anchocol2.text-center.borde-der.borde-izq 2
              td.anchocol2.text-center.borde-der 240,4
              td.anchocol3.text-center.borde-der 7
              td.anchocol3.text-center.borde-der 229,4
            tr.fondogris
              td.anchocol2.text-center.borde-der.borde-izq 3
              td.anchocol2.text-center.borde-der 246,3
              td.anchocol3.text-center.borde-der 8
              td.anchocol3.text-center.borde-der 255,5
            tr
              td.anchocol2.text-center.borde-der.borde-izq 4
              td.anchocol2.text-center.borde-der 239,4
              td.anchocol3.text-center.borde-der 9
              td.anchocol3.text-center.borde-der 235,5
            tr.fondogris
              td.anchocol2.text-center.borde-der.borde-abajo.borde-izq 5
              td.anchocol2.text-center.borde-der.borde-abajo 253,1
              td.anchocol3.text-center.borde-der.borde-abajo 10
              td.anchocol3.text-center.borde-der.borde-abajo 249,7
    h4.mt-5(data-aos="fade-down-left") Media
    p(data-aos="fade-down-right") Es el promedio matemático de los valores. Se representa con el símbolo: X
    p.mb-5(data-aos="fade-down-right") X = 224,3+240,4+246,3+239,4+253,1+ 261,7+229,4+255,5+235,5+ 249,7 = 243,53 mg Cl 10
    h4(data-aos="fade-down-left") Mediana
    p(data-aos="fade-down-right") Se ordenan los valores en forma creciente y la mediana será el valor central. Si el número de muestras es par, la mediana se calcula con el promedio de los dos valores centrales. Se representa Xmed.
    .row.justify-content-center
      .col-lg-8.col-md-10.col-sm-12
        .titulo-sexto.color-acento-contenido(data-aos="fade-down")
          h5 Tabla 5. 
          span Mediana
        .tabla-c(data-aos="fade-down-right")
          //-.div.table.table-responsive
          table
            caption.fondogris.fuente-size.fuente-regular Nota. Luzardo M (s,f) Toma de muestras
            tr
              td.fondo-9.text-center.borde-der.borde-izq.anchocol5.anchocol
                .h4 Muestra
              td.fondo-9.text-center.borde-der.anchocol5
                .h4 Mg de Cl
              td.fondo-9.text-center.borde-der.anchocol
              td.fondo-9.text-center.borde-der
              td.fondo-9.text-center.borde-der.anchocol4
            tr
              td.anchocol2.text-center.borde-der.borde-izq 1
              td.anchocol2.text-center.borde-der 224,3
              td.anchocol3.text-center.borde-der 
              td.anchocol3.text-center.borde-der
              <td class=" anchocol3 text-center borde-der fondo-blanco " rowspan="10">X med= 240,4+246,3= 243,42</td>
            tr
              td.anchocol2.text-center.borde-der.borde-izq 7
              td.anchocol2.text-center.borde-der 229,4
              td.anchocol3.text-center.borde-der 
              td.anchocol3.text-center.borde-der 
            tr
              td.anchocol2.text-center.borde-der.borde-izq 9
              td.anchocol2.text-center.borde-der 235,5
              td.anchocol3.text-center.borde-der 
              td.anchocol3.text-center.borde-der.borde-abajo
            tr
              td.anchocol2.text-center.borde-der.borde-izq 4
              td.anchocol2.text-center.borde-der 239,4
              td.anchocol3.text-center.borde-der 
              <td class=" anchocol3 text-center borde-der fondo-blanco" rowspan="3">Valores Centrales</td> 
            tr
              td.anchocol2.text-center.borde-der.borde-izq 2
              td.anchocol2.text-center.borde-der 240,4
              td.anchocol3.text-center.borde-der 
            tr
              td.anchocol2.text-center.borde-der.borde-izq 3
              td.anchocol2.text-center.borde-der 246,3
              td.anchocol3.text-center.borde-der
            tr
              td.anchocol2.text-center.borde-der.borde-izq 10
              td.anchocol2.text-center.borde-der 249,7
              td.anchocol3.text-center.borde-der 
              td.anchocol3.text-center.borde-der.borde-arriba 
            tr
              td.anchocol2.text-center.borde-der.borde-izq 5
              td.anchocol2.text-center.borde-der 253,1
              td.anchocol3.text-center.borde-der 
              td.anchocol3.text-center.borde-der 
            tr
              td.anchocol2.text-center.borde-der.borde-izq 8
              td.anchocol2.text-center.borde-der 255,5
              td.anchocol3.text-center.borde-der 
              td.anchocol3.text-center.borde-der 
            tr
              td.anchocol2.text-center.borde-der.borde-abajo.borde-izq 6
              td.anchocol2.text-center.borde-der.borde-abajo 261,7
              td.anchocol3.text-center.borde-der.borde-abajo 
              td.anchocol3.text-center.borde-der.borde-abajo
    h4.mt-5(data-aos="fade-down-left") Moda
    p.mb-5(data-aos="fade-down-right") Es el valor que se repite más veces en una serie. Esto se aplica para series muy grandes. En química analítica pocas veces se reporta utilizando la moda; en el ejercicio no hay ningún valor que se repita. Al reportar un resultado se debe indicar la dispersión de las medidas, por tanto, con solo reporta la media o la mediana no es suficiente. Para ello se debe calcular la desviación.
    h4(data-aos="fade-down-right") Desviación absoluta
    p.mb-0(data-aos="fade-down-right") Es la diferencia (en valor absoluto) de cada valor con respecto a la media.
    p.mb-5(data-aos="fade-down-right") Desviación media: es el promedio de las desviaciones absolutas.
    .row.justify-content-center
      .col-lg-8.col-md-10.col-sm-12
        .titulo-sexto.color-acento-contenido(data-aos="fade-down")
          h5 Tabla 6. 
          span Desviación absoluta
        .tabla-c(data-aos="fade-down-right")
          //-.div.table.table-responsive
          table
            caption.fondogris.fuente-size.fuente-regular Nota. Luzardo M (s,f) Desviación estándar
            tr
              td.fondo-9.text-center.borde-der.borde-izq.anchocol5.anchocol
                .h4 Muestra
              td.fondo-9.text-center.borde-der.anchocol5.anchocol
                .h4 Mg de Cl
              td.fondo-9.text-center.borde-der.anchocol5.anchocol
                h4 Desviación absoluta │Xi - media│
              td.fondo-9.text-center.borde-der.anchocol4
            tr.fondogris
              td.anchocol2.text-center.borde-der.borde-izq 1
              td.anchocol2.text-center.borde-der 224,3
              td.anchocol3.text-center.borde-der 
              <td class=" anchocol3 text-center borde-der fondo-9 anchocol5 " rowspan="11">
                p Desviación absoluta = │X - 
                  span.sobrerayado X
                  span │
                .row.align-items-center
                  .col-6
                    p Desviación media =
                  .col-6
                    img(src='@/assets/curso/tema12/ecuacion1.svg')
                p D media = 19, 2+14, 1+8, 1+4, 1+3, 1+2, 8+6, 2+9, 6+12, 0
                p.text-center.ms-5  10
                p.fuente-regular = 9,73…         9,7 
              </td>
            tr
              td.anchocol2.text-center.borde-der.borde-izq 7
              td.anchocol2.text-center.borde-der 229,4
              td.anchocol3.text-center.borde-der 
            tr.fondogris
              td.anchocol2.text-center.borde-der.borde-izq 9
              td.anchocol2.text-center.borde-der 235,5
              td.anchocol3.text-center.borde-der 
            tr
              td.anchocol2.text-center.borde-der.borde-izq 4
              td.anchocol2.text-center.borde-der 239,4
              td.anchocol3.text-center.borde-der 
            tr.fondogris
              td.anchocol2.text-center.borde-der.borde-izq 2
              td.anchocol2.text-center.borde-der 240,4
              td.anchocol3.text-center.borde-der 
            tr.fondogris
              td.anchocol2.text-center.borde-der.borde-izq 3
              td.anchocol2.text-center.borde-der 246,3
              td.anchocol3.text-center.borde-der 
            tr
              td.anchocol2.text-center.borde-der.borde-izq 10
              td.anchocol2.text-center.borde-der 249,7
              td.anchocol3.text-center.borde-der 
            tr.fondogris
              td.anchocol2.text-center.borde-der.borde-izq 5
              td.anchocol2.text-center.borde-der 253,1
              td.anchocol3.text-center.borde-der 
            tr
              td.anchocol2.text-center.borde-der.borde-izq 8
              td.anchocol2.text-center.borde-der 255,5
              td.anchocol3.text-center.borde-der 
            tr
              td.anchocol2.text-center.borde-der.borde-izq 6
              td.anchocol2.text-center.borde-der 261,7
              td.anchocol3.text-center.borde-der 
            tr.fondo-9
              td.anchocol2.text-center.borde-der.borde-abajo.borde-izq.anchocol5
                p 6
                p Media
                p Mediana
                p Desviación media
              td.anchocol2.text-center.borde-der.borde-abajo 
               p 261,7
               p 243,5
               p 243,4
               p 9,7
              td.anchocol3.text-center.borde-der.borde-abajo.anchocol5
                p 18,2   __
                p ______________
                p _
                p _____________

    h4.my-5(data-aos="fade-down-left") Desviación estándard
    .row.justify-content-center.mb-5
      .col-lg-8.col-md-8(data-aos="fade-down-right")
        p Representa la dispersión de las medidas individuales con respecto a la media y se utiliza en química analítica para reportar el resultado de un grupo de datos entre tres y veinte.
        p La desviación estándar y la media tienen las mismas unidades.
        p Para grupos mayores de veinte datos, se usa n en lugar de (n ─ 1). Algunas calculadoras científicas utilizan n o n-1 como fórmula predeterminada, sin tomar en cuenta el número de valores utilizados; por ello es recomendable consultar el manual de cada calculadora antes de utilizar esa función.
      .col-lg-4.col-md-4.fondo-18.px-5.pt-4.pb-3(data-aos="fade-down-left")
        img(src='@/assets/curso/tema12/ecuacion2.svg')
    hr
    h4.my-5(data-aos="fade-down-left") Reportar la desviación estándar
    p.mb-5 Se puede reportar la desviación estándar relativa a la media. Este valor no tiene unidades:
    .row.justify-content-center.mb-5
      .col-lg-6.col-md-12.fondo-18.px-5.py-4(data-aos="fade-down-right")
        img(src='@/assets/curso/tema12/ecuacion3.svg')
    hr
    .row.justify-content-center.my-5
      .col-xl-10.col-lg-12.mb-4(data-aos="fade-down-right")
        .tabla-c(data-aos="fade-down-right")
          //-.div.table.table-responsive
          table.text-center
            tr
              td.fondo-9.text-center.borde-der.borde-izq.anchocol5.anchocol.px-0.px-lg-2
                .h4 Muestra
              td.fondo-9.text-center.borde-der.anchocol5.px-0.px-lg-2
                .h4 Mg de Cl (X)
              td.fondo-9.text-center.borde-der.anchocol5.anchocol1.px-0.px-lg-2
                h4 Desviación absoluta │Xi - media│
              td.fondo-9.text-center.borde-der.anchocol5.anchocol1.px-0.px-lg-2
                h4 Cuadrado de las desviaciones absolutas (X - media)<sup>2</sup>
              td.fondo-9.text-center.borde-der.anchocol2.px-0.px-lg-2
            tr
              td.anchocol2.text-center.borde-der.borde-izq 1
              td.anchocol2.text-center.borde-der 
                p 22
                p.mb-0 4,3
              td.anchocol3.text-center.borde-der
                p 19,2
              td.anchocol3.text-center.borde-der
                p 368,6
              <td class="anchocol3 text-center borde-der fondo-9 anchocol5" rowspan="10" style="padding-left: 10px; padding-right: 10px;">
                img.mx-0(src='@/assets/curso/tema12/ecuacion4.svg')
                img.mt-5.mx-0(src='@/assets/curso/tema12/ecuacion5.svg')
              </td>
            tr
              td.anchocol2.text-center.borde-der.borde-izq 7
              td.anchocol2.text-center.borde-der
                p 22
                p.mb-0 9,4
              td.anchocol3.text-center.borde-der 
                p 14,1
              td.anchocol3.text-center.borde-der
                p 198,8
            tr
              td.anchocol2.text-center.borde-der.borde-izq 9
              td.anchocol2.text-center.borde-der 
                p 23
                p.mb-0 5,5
              td.anchocol3.text-center.borde-der 
                p 8,1
              td.anchocol3.text-center.borde-der
                p 65,6
            tr
              td.anchocol2.text-center.borde-der.borde-izq 4
              td.anchocol2.text-center.borde-der 
                p 23
                p.mb-0 9,4
              td.anchocol3.text-center.borde-der 
                p 4,1
              td.anchocol3.text-center.borde-der
                p 16,8
            tr
              td.anchocol2.text-center.borde-der.borde-izq 2
              td.anchocol2.text-center.borde-der 
                p 24
                p.mb-0 0,4
              td.anchocol3.text-center.borde-der 
                p 3,1
              td.anchocol3.text-center.borde-der
                p 9,6
            tr
              td.anchocol2.text-center.borde-der.borde-izq 3
              td.anchocol2.text-center.borde-der 
                p 24
                p.mb-0 6,3
              td.anchocol3.text-center.borde-der 
                p 2,8
              td.anchocol3.text-center.borde-der
                p 7,8
            tr
              td.anchocol2.text-center.borde-der.borde-izq 10
              td.anchocol2.text-center.borde-der 
                p 24
                p.mb-0 9,7
              td.anchocol3.text-center.borde-der 
                p 6,2
              td.anchocol3.text-center.borde-der
                p 38,4
            tr
              td.anchocol2.text-center.borde-der.borde-izq 5
              td.anchocol2.text-center.borde-der
                p 25
                p.mb-0 3,1
              td.anchocol3.text-center.borde-der 
                p 9,6
              td.anchocol3.text-center.borde-der
                p 92,2
            tr
              td.anchocol2.text-center.borde-der.borde-izq 8
              td.anchocol2.text-center.borde-der 
                p 25
                p.mb-0 5,5
              td.anchocol3.text-center.borde-der 
                p 12,0
              td.anchocol3.text-center.borde-der
                p 144,0
            tr
              td.anchocol2.text-center.borde-der.borde-izq 6
              td.anchocol2.text-center.borde-der 
                p 26
                p.mb-0 1,7
              td.anchocol3.text-center.borde-der
                p 18,2
              td.anchocol3.text-center.borde-der
                p 331,2
      .col-lg-2.col-md-4.col-sm-6.col-8(data-aos="fade-down-right")
        .div.table.table-responsive
          table
            tr.fondogris
              td.text-center.borde-der.borde-izq.anchocol5.anchocol2.borde-arriba
                p.mb-0 Media
                p 243,5
            tr
              td.text-center.borde-der.borde-izq.anchocol5
                p.mb-0 Desviación media
                p 9,7
            tr.fondogris
              td.text-center.borde-der.borde-izq.anchocol5.borde-abajo
                p.mb-0 Suma de los cuadrados de las desviaciones
                p 1273,2
    hr
    h4.my-5(data-aos="fade-down-left") Cifras significativas del resultado y de la desviación estándar
    p(data-aos="fade-down-right") Las cifras significativas de la desviación estándar dependen directamente de la incertidumbre de la media. La desviación estándar se reporta con el mismo número de decimales de la media.
    p.mb-5(data-aos="fade-down-right") En el caso de la determinación del contenido de cloro - Cl en las muestras de agua, la media se debe reportar con cuatro cifras significativas, ya que todos los datos tienen cuatro cifras significativas (un solo decimal). La desviación estándar (absoluta) debe reportarse con igual número de decimales que la media: un solo decimal.
    .row.justify-content-center
      .col-lg-8.col-md-10.col-sm-12.p-4.fondo-19(data-aos="fade-down-right")
        p.mb-0 El resultado del análisis de las muestras de agua se reportará:
        p 243,5 ± 11,9 mg/L de Cl
        p.mb-0 Otra medida de dispersión es la varianza, la cual se calcula elevando al cuadrado la desviación estándar (S2).
        p En este caso la varianza es = (11,9) 2 = 141,6
    h4.my-5(data-aos="fade-down-left") Error en la medición
    p.mb-5(data-aos="fade-down-right") Para calcular el error es necesario conocer el valor real o valor verdadero. En ejercicio se reporta por laboratorio externo de control un valor 250,0 mg de CL.
    .tarjeta--container.row.mb-5.justify-content-center
      .col-xl-6.col-lg-8.tarjeta.color-secundario.p-5(data-aos="fade-down-right")
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/tema12/EA.svg')
        .text-white  
          h2.text-center Error absoluto (E)
          p.text-center Es la diferencia entre la media y el valor considerado como verdadero o valor real. El error se reporta con signo positivo (error por exceso) o con signo negativo (error por defecto).
        .row.justify-content-center.mb-4
          .col-md-10.col-sm-12.fondo-blanco.py-4
            img(src='@/assets/curso/tema12/ecuacion6.svg')
      .col-xl-6.col-lg-8.tarjeta.color-primario.p-5(data-aos="fade-down-left")
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/tema12/ER.svg')
          
        h2.text-center Error relativo (Er):
        p.text-center Se relaciona con el valor verdadero y se reporta como porcentaje.
        p.text-center El signo negativo indica un error por defecto, el valor reportado es menor que el valor considerado como verdadero.
        .row.justify-content-center.mb-4
          .col-md-10.col-sm-12.fondo-blanco.py-4
            img(src='@/assets/curso/tema12/ecuacion7.svg')
    h4.my-5(data-aos="fade-down-left") Intervalos de confianza
    p(data-aos="fade-down-right") También conocidos como límites de confianza, es el intervalo de valores alrededor de la media, dentro del cual es probable que se encuentre el valor verdadero. La expresión general para los límites de confianza (LC) es la siguiente:
    .row.justify-content-center
      .col-auto.fondo-18.px-5.py-4(data-aos="fade-down-right")
        p.text-center.mb-0 LC = 
          span.sobrerayado X 
          span ± z s  
    p.my-5(data-aos="fade-down-right") Donde s es la desviación estándar y z se obtiene de la siguiente tabla:
    .row.justify-content-center
      .col-lg-4.col-md-8.col-sm-12
        .titulo-sexto.color-acento-contenido(data-aos="fade-down")
          h5 Tabla 7. 
          span Valores de Z
          //-.tabla-c(data-aos="fade-down-right")
        .div.table.table-responsive
          table
            caption.fondogris.fuente-size.fuente-regular Skoog (2001) Valores de z para varios niveles de confianza
            tr
              td.fondo-9.text-center.borde-der.borde-izq.anchocol5.anchocol6
                .h4 Nivel de confianza (%)
              td.fondo-9.text-center.borde-der.anchocol5.anchocol6
                .h4 Valor de Z
            tr.fondogris
              td.anchocol2.text-center.borde-der.borde-izq 50
              td.anchocol2.text-center.borde-der 0,67
            tr
              td.anchocol2.text-center.borde-der.borde-izq 68
              td.anchocol2.text-center.borde-der 1,00
            tr.fondogris
              td.anchocol2.text-center.borde-der.borde-izq 80
              td.anchocol2.text-center.borde-der 1,29
            tr
              td.anchocol2.text-center.borde-der.borde-izq 90 
              td.anchocol2.text-center.borde-der 1,64
            tr.fondogris
              td.anchocol2.text-center.borde-der.borde-izq 95 
              td.anchocol2.text-center.borde-der 1,96
            tr
              td.anchocol2.text-center.borde-der.borde-izq 95,4
              td.anchocol2.text-center.borde-der 2,00
            tr.fondogris
              td.anchocol2.text-center.borde-der.borde-izq 99
              td.anchocol2.text-center.borde-der 2,58
            tr
              td.anchocol2.text-center.borde-der.borde-izq 99,7 
              td.anchocol2.text-center.borde-der 3,00
            tr.fondogris
              td.anchocol2.text-center.borde-der.borde-izq 99,9 
              td.anchocol2.text-center.borde-der 3,29
    h4.my-5(data-aos="fade-down-left") Análisis intervalos de confianza
    p(data-aos="fade-down-right") Entonces el intervalo de confianza utilizando un nivel de confianza del 90% para el análisis es:
    p(data-aos="fade-down-right") 243,5 ± 11,9 mg Cl/L, con la media (243,5 mg) y la desviación estándar absoluta (11,9 mg).
    p(data-aos="fade-down-right") De la tabla de valores de z para varios niveles de confianza se obtiene el valor de z = 1,64 para un 90% de confianza y se calcula LC (límites de confianza).
    .row.justify-content-center.my-5
      .col-auto.fondo-18.px-5.py-4(data-aos="fade-down-right")
        p.mb-0 LC= X ± zs = 234,5 ± (1,64) X 11,9 =234,5+19,5
    p(data-aos="fade-down-right") Por tanto, el intervalo de confianza es: (224,0 ─ 263,0) mg de CL/L
    p(data-aos="fade-down-right") El valor considerado como verdadero es 250,0 mg Cl/L (reportado por el laboratorio control), se encuentra dentro el intervalo de confianza para el nivel de confianza del 90%
    h4.my-5(data-aos="fade-down-left") Curva calibración
    p(data-aos="fade-down-right") Se preparan patrones del analito que cubran un intervalo adecuado de concentraciones, y se mide la señal analítica  proporcionada por los mismos. La medida de la concentración mediante un método instrumental se basa en la existencia de una relación proporcional entre dicha concentración y la señal analítica o respuesta que genera un instrumento.
    p(data-aos="fade-down-right") Generalmente esta relación es lineal, de modo que puede expresarse como:
    .row.justify-content-center.my-5
      .col-auto.fondo-18.px-5.py-4(data-aos="fade-down-right")
        p.mb-0 y =a+b·CA
    p.mb-5(data-aos="fade-down-right") Donde CA es la concentración del analito, y la señal medida, a la ordenada en el origen y b la pendiente de la recta.
    h4.mb-5(data-aos="fade-down-left") Ecuación recta
    p.mb-5(data-aos="fade-down-right") La ecuación de la recta se obtiene mediante calibración con disoluciones de concentración perfectamente conocida (disoluciones patrón) a partir de la medida de la señal analítica proporcionada por éstas. Los pares de valores concentración-señal se ajustan a una recta, a partir de la cual pueden obtenerse la concentración del analito en muestras desconocidas.
    .row.justify-content-center
      .col-lg-10.col-md-12
        .titulo-sexto.color-acento-contenido(data-aos="fade-down")
          h5 Figura 1. 
          span Disoluciones del analito de concentración conocida y creciente
        .row.justify-content-center.align-items-center.fondo-20.py-5.px-4
          .col-lg-6.col-md-12.mb-4(data-aos="fade-down-right")
            img(src='@/assets/curso/tema12/fig1.svg')
          .col-lg-6.col-md-12
            ul.lista-ul
              li 
                i.fas.fa-check
                | Paso 1: preparación de los patrones.
              li 
                i.fas.fa-check
                | Paso 2: obtención de la relación señal - concentración.
              li 
                i.fas.fa-check
                | Paso 3: uso de la curva de calibrado.
    h4.my-5(data-aos="fade-down-left") señal-concentración y recta
    p.mb-5(data-aos="fade-down-right") Se traza un gráfico con las señales frente a la concentración de analito y se calcula la recta que “mejor” se ajusta a los datos mediante un ajuste por mínimos cuadrados. De esta forma se obtiene la pendiente (b) y la ordenada (a) en el origen que definen la recta.
    .row.justify-content-center
      .col-lg-8.col-md-12
        .titulo-sexto.color-acento-contenido(data-aos="fade-down")
          h5 Figura 2. 
          span Señal-concentración y recta ajustada por mínimos cuadrados
        .row.justify-content-center.align-items-center.fondo-20.py-5
          .col-lg-10.col-md-12.mb-4(data-aos="fade-down-right")
            img(src='@/assets/curso/tema12/fig2.svg')
    h4.my-5(data-aos="fade-down-left") Cálculo excel
    p.mb-5(data-aos="fade-down-right") En la actualidad las calculadoras científicas realizan el ajuste por mínimos cuadrados y, dicho ajuste, también puede realizarse en el ordenador mediante la hoja de cálculo EXCEL.
    p.mb-5(data-aos="fade-down-right") A continuación, se brinda una plantilla para el ajuste por mínimos cuadrados mediante la hoja de cálculo EXCEL y dos tutoriales que le ayudarán a utilizar dicha plantilla y la herramienta de gráficos de dicho programa.
    .row.justify-content-center.my-5
      .col-xl-10.col-lg-12(data-aos="fade-down-right")
        .row.justify-content-center.align-items-center.fondo-5.px-2.py-4.redondearpuntas.mb-4.flex
          .col-xxl-2.col-lg-3.col-md-3.col-sm-4.col-5
            img(src='@/assets/curso/tema12/web.svg')

          .col-xxl-10.col-lg-12.col-md-12
            .row.align-items-center
              .col-xxl-9.col-md-9.text-white
                h3.mb-0 Pantalla EXCEL
                p.text-small.mb-4.mb-md-0 Para el ajuste por mínimos cuadrados. https://drive.google.com/file/d/1gWslpfJG7dhGpToHu2ZdkZefn1oPCcJl/view?usp=sharing
              .col-xxl-3.col-md-3
                a.boton.color-acento-botones(:href="('https://drive.google.com/file/d/1gWslpfJG7dhGpToHu2ZdkZefn1oPCcJl/view?usp=sharing')" target="_blank")
                  span Enlace web
                  i.fas.fa-link
            .row.align-items-center.my-3
              .col-xxl-9.col-md-9.text-white
                h3.mb-0 Tutorial 1
                p.text-small.mb-0.mb-md-0 Que explica cómo utilizar la plantilla de EXCEL.
                p.text-small.mb-4.mb-md-0 http://mmedia.uv.es/buildhtml?lang=es_ES&user=martiny&name=tutorial_excel_plantilla.swf&path=/&id=6534
              .col-xxl-3.col-md-3
                a.boton.color-acento-botones(:href="('http://mmedia.uv.es/buildhtml?lang=es_ES&user=martiny&name=tutorial_excel_plantilla.swf&path=/&id=6534')" target="_blank")
                  span Enlace web
                  i.fas.fa-link         
            .row.align-items-center
              .col-xxl-9.col-md-9.text-white
                h3.mb-0 Tutorial 2
                p.text-small.mb-0.mb-md-0 Que explica cómo utilizar la herramienta gráficos de EXCEL, para obtener una recta ajustada por mínimos cuadrados.
                p.text-small.mb-4.mb-md-0 http://mmedia.uv.es/buildhtml?lang=es_ES&user=martiny&name=tutorial_excel_graficos.swf&path=/&id=6530
              .col-xxl-3.col-md-3
                a.boton.color-acento-botones(:href="('http://mmedia.uv.es/buildhtml?lang=es_ES&user=martiny&name=tutorial_excel_graficos.swf&path=/&id=6530')" target="_blank")
                  span Enlace web
                  i.fas.fa-link

    h4.my-5(data-aos="fade-down-left") Señal analítica
    p.mb-5(data-aos="fade-down-right") Se mide la señal analítica para las muestras desconocidas y se interpola en la recta de calibrado para obtener valores de concentración de analito.
    .row.justify-content-center
      .col-lg-8.col-md-12
        .titulo-sexto.color-acento-contenido(data-aos="fade-down")
          h5 Figura 3. 
          span Obtención de la concentración de analito en las muestras a partir de la gráfica y la recta
        .row.justify-content-center.align-items-center.fondo-20.py-5
          .col-lg-10.col-md-12.mb-4(data-aos="fade-down")
            img(src='@/assets/curso/tema12/fig3.svg')   

    p.my-5 Finalmente, para obtener la concentración de analito en la muestra hay que tener en cuenta en los cálculos las posibles diluciones a las que se ha sometido la muestra para obtener las disoluciones M1, M2 y M3 de medida.
</template>

<script>
export default {
  name: 'Tema12',
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
