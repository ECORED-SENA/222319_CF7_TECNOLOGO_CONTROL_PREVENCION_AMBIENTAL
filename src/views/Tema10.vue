<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos="fade-down-right")
      .titulo-principal__numero.text-white
        span 10
      h1 Protocolo de análisis de residuos sólidos
    p(data-aos="fade-down-left") A continuación le presentamos una gráfica de estudio del protocolo de análisis de residuos sólidos.
    p(data-aos="fade-down-right") Un residuo sólido, es aquel material desechado tras su vida útil, y que por lo general por sí solo carece de valor económico.
    p(data-aos="fade-down-right") Se componen principalmente de desechos procedentes de materiales utilizados en la fabricación, transformación o utilización de bienes de consumo. Dentro de los residuos se debe establecer que existen dos grandes grupos, como 
      span.text-bold peligrosos y no peligrosos.
    .row.my-5.justify-content-center
      .col-sm-10.col-lg-5.col-xl-5.col-12.mb-4.mb-xl-0(data-aos="fade-down-right")
        .tarjeta.tarjeta-flip.color-secundario(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema10/flip1.png')})`}")
              div.crd_txt.fondo-card-1
                h4.text-center Los no peligrosos
                p.text-center.px-5 Los no peligrosos no conllevan ningún tipo de riesgo para la población o el medio ambiente de forma contundente y estos se clasifican en…
            .tarjeta-flip__contenido.p-4.p-xl-5
              h4 Los no peligrosos
              p • 
                span.text-bold Ordinarios. 
                span Los cuales son los que se producen en las actividades rutinarias en los hogares, oficinas, hospitales o centros educativos. 

              p • 
                span.text-bold Biodegradables. 
                span Son aquellos que se descomponen de forma sencilla en el medio ambiente. 

              p • 
                spanspan.text-bold Inertes. 
                span Tardan un poco más de tiempo en descomponerse, en estos se encuentra madera, papel o cartón. 

              p • 
                span.text-bold Reciclables. 
                span Son aquellos que pueden tener un segundo periodo de uso, ya sea transformado o no.

      .col-sm-10.col-lg-5.col-xl-5.col-12.mb-4.mb-xl-0(data-aos="fade-down-left")
        .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img.imgsize(:style="{'background-image': `url(${require('@/assets/curso/tema10/flip2.png')})`}")
              div.crd_txt1.fondo-card-2
                h4.text-center La gestión de residuos
                p.text-center.px-4.px-sm-5 La gestión de los residuos sólidos implica un protocolo, iniciando en la separación y almacenamiento en el origen, la recogida (por la empresa recolectora), el transporte y la eliminación o transformación.
            .tarjeta-flip__contenido.p-4.p-xl-5
              h4.text-center La gestión de residuos
              p • Selección y separación. 
              p • Recolección en el punto y transporte. 
              p • Separación y/o clasificación. 
              p • Aprovechamiento en el caso que sea posible. 
              p • Tratamiento.
              p • Disposición final.
    .row.justify-content-center.my-5
      .col-lg-10.col-sm-12.mt-5.mt-lg-0
        .row.mb-4.align-items-center.p-4.fondo-8.justify-content-center.mt-5.mt-lg-0
          .col-lg-1.col-md-2.col-sm-2.col-3.mb-4.mb-sm-0(data-aos="fade-down-right")
            img(src='@/assets/curso/tema4/alerta.svg')
          .col-lg-11.col-md-10.col-sm-10.col-12(data-aos="fade-down-left")
            p.mb-0 Dentro de los peligrosos están aquellos que pueden generar peligro para las personas o el medio ambiente, y tiene propiedades tóxicas y/o explosivas. 
    p.text-center.mb-5(data-aos="fade-down-right") A continuación, estudie mediante la actividad propuesta, la clasificación de los Residuos o desechos peligrosos.
    TabsA.color-acento-botones.mb-5.nuevo-margen-tab(data-aos="fade-down")

      .tarjeta.fondo-7.p-4(titulo="Peligroso reactivo")
        h4 Peligroso reactivo
        p Característica que presenta un residuo o desecho cuando al mezclarse o ponerse en contacto con otros elementos, compuestos, sustancias o residuos tiene cualquiera de las siguientes propiedades:
        p a) Generar gases, vapores y humos tóxicos en cantidades suficientes para provocar daños a la salud humana o al ambiente cuando se mezcla con agua. 
        p b) Poseer entre sus componentes sustancias tales como cianuros, sulfuros, peróxidos orgánicos que por reacción liberen gases, vapores o humos tóxicos en cantidades suficientes para poner en riesgo la salud humana o el ambiente. 
        p c) Ser capaz de producir una reacción explosiva o detonante bajo la acción de un fuerte estímulo inicial o de calor en ambientes confinados. 
        p d) Aquel que produce una reacción endotérmica o exotérmica al ponerse en contacto con el aire, el agua o cualquier otro elemento o sustancia. 
        p e) Provocar o favorecer la combustión.

      .tarjeta.fondo-7.p-4(titulo="Peligroso explosivo")
        h4 Peligroso explosivo
        p Un residuo o mezcla de residuos es explosivo cuando en estado sólido o líquido de manera espontánea, por reacción química, puede desprender gases a una temperatura, presión y velocidad tales que puedan ocasionar daño a la salud humana o al ambiente y además presentar cualquiera de las siguientes propiedades: 
        p a) Formar mezclas potencialmente explosivas con el agua. 
        p b) Ser capaz de producir fácilmente una reacción de descomposición detonante o explosiva a temperatura de 25°C y presión de 1 atmósfera.
      
      .tarjeta.fondo-7.p-4(titulo="Peligroso inflamable")
        h4 Peligroso inflamable
        p Característica que presenta un residuo o desecho cuando en presencia de una fuente de ignición, puede arder bajo ciertas condiciones de presión y temperatura, o presentar cualquiera de las siguientes propiedades:
        p a) Ser un gas que a una temperatura de 20°C y una atmósfera de presión arde en una mezcla igual o menor al 13% del volumen del aire.
        p b) Ser un líquido cuyo punto de inflamación es inferior a 60°C de temperatura, con excepción de las soluciones acuosas con menos de 24% de alcohol en volumen. 
        p c) Ser un sólido con la capacidad bajo condiciones de temperatura de 25 °C y presión de 1.0 atmósfera, de producir fuego por fricción, absorción de humedad o alteraciones químicas espontáneas y quema vigorosa, y persistentemente dificultando la extinción del fuego. Ser un oxidante que puede liberar oxígeno y, como resultado, estimular la combustión y aumentar la intensidad del fuego en otro material.
    .row.justify-content-center.align-items-center.mt-5
      .col-lg-4.col-md-8.col-sm-10.col-12(data-aos="fade-down-right")
        p El concepto de evaluación involucra un factor adicional: la medición. Evaluar es medir resultados obtenidos contra un parámetro establecido. Sin embargo, resulta poco objetivo tratar de evaluar los resultados contra un parámetro cuantitativo único, pues se deben considerar también elementos cualitativos que son difíciles de medir, (Fernández, 2007).
        p Lo dicho hasta aquí, supone que las métricas del marketing pueden aclarar algunas de las cuestiones clave como:
        ul.lista-ul
          li 
            i.fas.fa-check
            | ¿Cuál es el valor real de la organización?
          li 
            i.fas.fa-check
            | ¿Somos competitivos en innovación y marca? 
          li 
            i.fas.fa-check
            | ¿Están las estrategias orientadas a los clientes adecuados?
      .col-lg-4.col-md-8.col-sm-10.col-12(data-aos="fade-down-left")
        img(src='@/assets/curso/tema10/imagen1.jpg')
    separador
    #t_10_1.titulo-segundo.color-acento-contenido(data-aos="fade-down-right")
      h2 10.1 Muestreo y la preparación de la muestra
    p.mb-5(data-aos="fade-down-right") Una característica para realizar el muestreo de los sólidos en el laboratorio, es hacer un trabajo específico, con la colaboración de los técnicos o encargados de los mismos, para determinar las características de los residuos sólidos producidos en cada uno de estos espacios o lugares, determinando el número de personas y el aforo de los residuos generados.
    .row.mb-5
      .col-auto(data-aos="fade-down-left")
        h3.text-white.text-center.fondo-4 Caracterización física
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema10/imagen2.jpg')})`}"
      )
      .bloque-texto-g__texto.px-4.py-5
        p Este proceso se lleva a cabo en el sitio de almacenamiento central de los residuos. Para realizar el ensayo se acondiciona el lugar y se debe instalar básculas y dinamómetros para el pesaje de los mismos. Allí se pesa el material y se registran los datos en un formato para el control de bolsas; luego, se procede a clasificar la muestra por tipo de residuo, los cuales deben ser pesadas una a una.
    AcordionA(data-aos="fade-down-right").my-5.pe-4(tipo="a" clase-tarjeta="tarjeta tarjeta--gris")
      .row.justify-content-center(titulo="Materia orgánica")
        .col-12.mb-4.mb-lg-0.ps-5
          .row
            .col-11.ms-4
              p Cáscaras y restos de alimentos, madera, follaje y otros. Papel: papel de imprenta y escritura, papel archivo, papel de oficina, sobres de cartas, papel sucio, papel kraft (bolsas, sobres) papel de desperdicio mezclado, papel higiénico, servilletas, papel parafinado, cartón.
      .row.justify-content-center(titulo="Plásticos")
        .col-12.mb-4.mb-lg-0.ps-5
          .row
            .col-11.ms-4
              p PET (polietileno tereftalato) (1) Botellas para refrescos; PE-AD (Polietileno de alta densidad) (2) botellas para leche, agua, zumos, detergentes; PVC (policloruro de vinilo) (3) botellas de agua y aceite para ensaladas; PE-BD (polietileno de baja densidad) (4) película de envolver; PP (polipropileno) (5) comidas rápidas, película, botellas de salsas; PS (poliestireno) (6) botellas de fármacos, tapas de espuma, entre otros; otros (7) cueros y textiles.
      .row.justify-content-center(titulo="Metales")
        .col-12.mb-4.mb-lg-0.ps-5
          .row
            .col-11.ms-4
              p Ferrosos y no ferrosos. Vidrio: vidrio blanco, ámbar y verde. Otros: papel laminado, tetra pak, carbón y cenizas, carbón de fotocopiadora. Peligrosos: químicos, pilas, baterías, fármacos, etc. Materiales pétreos.
    .row.mb-5
      .col-auto(data-aos="fade-down-left")
        h3.text-white.text-center.fondo-4  Análisis físico-químicos y microbiológicos
    .row.justify-content-center
      .col-lg-7.col-md-12(data-aos="fade-down-right")
        p Según Yepes (2007): 
        p Para realizar ensayos de laboratorio se aconseja realizarlo sobre material orgánico y para ello se puede aplicar el método de cuarteo de la siguiente forma. 
        p Con la materia orgánica encontrada se conforma un montículo, que se homogeniza mezclándolo con una pala, formando luego un círculo en el piso. Posteriormente se procede a dividirlo en cuatro partes y se seleccionan dos opuestas para formar otra muestra representativa más pequeña.
        p La muestra menor se vuelve a mezclar y se divide nuevamente en cuatro partes, se escogen dos opuestas y se forma otra más pequeña. Esta operación se repite hasta obtener el tamaño de la muestra necesaria para hacer las mediciones respectivas. Obteniendo una muestra representativa para su transporte al laboratorio. (p.11)
      .col-lg-5.col-md-12(data-aos="fade-down-left")
        img(src='@/assets/curso/tema10/imagen3.jpg')
    hr

    .row.mb-5
      .col-auto(data-aos="fade-down-left")
        h3.text-white.text-center.fondo-4 Preservación y transporte de las muestras 
    .row.justify-content-center
      .col-lg-7.col-md-12(data-aos="fade-down-right")
        p Según Cano L (2017):
        p Después de hacer los respectivos cuarteos, una vez obtenidas las muestras, estas son colocadas en un cooler y selladas para evitar la contaminación y facilitar su traslado.
        p Una vez en el laboratorio se depositan las muestras en un refrigerador adaptado a 8°C de temperatura.
        p De esta manera, se evita pérdidas de humedad por evaporación o reacciones aceleradas de descomposición. (P.28)
      .col-lg-5.col-md-12(data-aos="fade-down-left")
        img(src='@/assets/curso/tema10/imagen4.jpg')
    hr

    .row.mb-5
      .col-auto(data-aos="fade-down-left")
        h3.text-white.text-center.fondo-4 Preparación de las muestras para el análisis
    .row.justify-content-center
      .col-lg-7.col-md-12(data-aos="fade-down-right")
        p Según Cano (2017): 
        p Una vez obtenidas las muestras en el laboratorio, se procede a realizar la caracterización de la misma, esto quiere decir que se pesa cada categoría de residuo para obtener cuál es su porcentaje en peso respecto al total de la muestra.
        p Después de saber cuál es el porcentaje de cada categoría de residuo, se hace una relación respecto a los 100g que se necesita de muestra para los análisis de laboratorio, con el fin de tener una muestra representativa.
        p Posteriormente se debe realizar el picado de las muestras de cada categoría en pedazos no mayores a 1cm, con la ayuda de tijeras o la espátula de laboratorio, para después trasladarlas a los crisoles de porcelana. (p.28)
      .col-lg-5.col-md-12(data-aos="fade-down-left")
        img(src='@/assets/curso/tema10/imagen5.jpg')
    hr

    .row.mb-5
      .col-auto(data-aos="fade-down-left")
        h3.text-white.text-center.fondo-4  Determinación de humedad y cenizas

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema10/imagen6.jpg')})`}"
      )
      .bloque-texto-g__texto.px-4.py-5
        p De acuerdo a MinAmbiente (2017): 
        p La humedad de los residuos sólidos está referida a la cantidad total de agua que estos contienen. El cálculo de este parámetro es importante para estimar la potencialidad de los residuos sólidos para la generación de lixiviados, y la consecuente facilitación de la degradación de los mismos (digestión aerobia y anaerobia). (p.43)
    p.mt-5 Según Cano (2016):
    p.mb-5 Después de picar la muestra y obtener los 100g de residuos homogenizado, se procede de la siguiente manera:
    .row.mb-3.fondo-11.redondearpuntas.align-items-center.p-3.justify-content-center
      .col-lg-1.col-md-2.col-sm-2.col-3.mb-4.mb-sm-0(data-aos="fade-down-right")
        img(src='@/assets/curso/tema5/1.svg')
      .col-lg-11.col-md-10.col-sm-10.col-12(data-aos="fade-down-left")
        p Se toman tres crisoles de porcelana de 50 mL, se los etiqueta y se los pesa en la balanza analítica.
    .row.mb-3.fondo-11.redondearpuntas.align-items-center.p-3.justify-content-center
      .col-lg-1.col-md-2.col-sm-2.col-3.mb-4.mb-sm-0(data-aos="fade-down-right")
        img(src='@/assets/curso/tema5/2.svg')
      .col-lg-11.col-md-10.col-sm-10.col-12(data-aos="fade-down-left")
        p Se anota el peso con las cifras que proporciona la balanza en peso crisol.
    .row.mb-3.fondo-11.redondearpuntas.align-items-center.p-3.justify-content-center
      .col-lg-1.col-md-2.col-sm-2.col-3.mb-4.mb-sm-0(data-aos="fade-down-left")
        img(src='@/assets/curso/tema5/3.svg')
      .col-lg-11.col-md-10.col-sm-10.col-12(data-aos="fade-down-right")
        p Se procede a aforar el crisol con la muestra húmeda y se anota con 2 cifras significativas en Peso crisol + Muestra húmeda.
    .row.mb-3.fondo-11.redondearpuntas.align-items-center.p-3.justify-content-center
      .col-lg-1.col-md-2.col-sm-2.col-3.mb-4.mb-sm-0(data-aos="fade-down-right")
        img(src='@/assets/curso/tema5/4.svg')
      .col-lg-11.col-md-10.col-sm-10.col-12(data-aos="fade-down-left")
        p Se introducen los crisoles en la estufa automática.
    .row.mb-3.fondo-11.redondearpuntas.align-items-center.p-3.justify-content-center
      .col-lg-1.col-md-2.col-sm-2.col-3.mb-4.mb-sm-0(data-aos="fade-down-left")
        img(src='@/assets/curso/tema5/5.svg')
      .col-lg-11.col-md-10.col-sm-10.col-12(data-aos="fade-down-right")
        p La estufa se la programa a 105 °C durante un periodo de 24 horas.
    .row.mb-3.fondo-11.redondearpuntas.align-items-center.p-3.justify-content-center
      .col-lg-1.col-md-2.col-sm-2.col-3.mb-4.mb-sm-0(data-aos="fade-down-right")
        img(src='@/assets/curso/tema10/6.svg')
      .col-lg-11.col-md-10.col-sm-10.col-12(data-aos="fade-down-left")
        p Pasado este periodo de tiempo, se espera durante aproximadamente 10 minutos antes de abrir la estufa. Luego se retira cada crisol con pinzas y se los pesa nuevamente, su valor se lo anota en peso crisol + residuo seco.
    .row.mb-5.fondo-11.redondearpuntas.align-items-center.p-3.justify-content-center
      .col-lg-1.col-md-2.col-sm-2.col-3.mb-4.mb-sm-0(data-aos="fade-down-left")
        img(src='@/assets/curso/tema10/7.svg')
      .col-lg-11.col-md-10.col-sm-10.col-12(data-aos="fade-down-right")
        p Una vez llenados los datos en la tabla siguiente  y se halla el porcentaje de humedad contenido en los RS. (p.30).
    .tabla-c(data-aos="fade-down-right")
      table
        tr
          td.fondo-9.anchocol1.text-center.borde-der
            .h4 No.1
          td.fondo-9.anchocol1.text-center.borde-der
            .h4 Peso crisol (g)
          td.fondo-9.anchocol1.text-center.borde-der
            .h4 Peso crisol + muestra húmeda (g)
          td.fondo-9.anchocol1.text-center.borde-der
            .h4 Peso neto residuos (g)
          td.fondo-9.anchocol1.text-center.borde-der
            .h4 Peso crisol + Residuos secos (g)
          td.fondo-15.anchocol1.text-center.borde-der
            .h4 Peso neto residuos sin humedad (g) (Residuos - peso Crisol)
          td.fondo-16.anchocol1.text-center
            .h4 % Humedad total
        tr
          th.anchocol1.text-center.borde-der 1
          td.anchocol1.borde-der
          td.anchocol1.borde-der
          td.anchocol1.borde-der
          td.anchocol1.borde-der 
          td.anchocol1.borde-der 
          td.anchocol1 
    //--Título fondo azul
    .row.my-5
      .col-auto(data-aos="fade-down-left")
        h3.text-white.text-center.fondo-4 Cálculo para la determinación del porcentaje de humedad
    .row.justify-content-center
      .col-lg-4.col-md-12(data-aos="fade-down-right")
        p Donde: 
        p.mb-0 A = Peso del crisol más la muestra húmeda (g)
        p.mb-0 B = Peso del crisol más la muestra seca (g)
        p.mb-0 C = Peso del crisol (g)
        p Determinación del porcentaje de cenizas (%C)
      .col-lg-4.col-md-12(data-aos="fade-down-left")
        img(src='@/assets/curso/tema10/ecuacion1.svg')
    p.my-5(data-aos="fade-down-right") Se toma tres crisoles de porcelana de 50 mL, se los etiqueta y se los pesa en la balanza analítica. 
    .row.justify-content-center.mb-5
      .col-lg-7.col-md-12(data-aos="fade-down-right")
        ul.lista-ul
          li
            i.fas.fa-check
            | Se anota el peso con 2 cifras significativas en peso crisol. 
          li
            i.fas.fa-check
            | Se procede a aforar el crisol con la muestra húmeda y se anota el valor con 2 cifras significativas en peso crisol + muestra. 
          li
            i.fas.fa-check
            | Se introduce los crisoles en la mufla automática. 
          li
            i.fas.fa-check
            | Se programa la mufla a 900 °C durante un periodo de 6 horas. 
          li
            i.fas.fa-check
            | Pasado este periodo de tiempo, se espera mínimo 45 minutos antes de extraer los crisoles de la mufla. Este procedimiento se lo realiza con las pinzas para el crisol. 
          li
            i.fas.fa-check
            | Pesar y anotar el peso. 
          li
            i.fas.fa-check
            | Una vez llenado los datos en la tabla siguiente y basados en la ecuación, se procede a determinar el porcentaje de cenizas obtenidas del proceso de incineración de los RS. (p.48).
      .col-lg-5.col-md-12(data-aos="fade-down-left")
        img(src='@/assets/curso/tema10/imagen7.jpg')
    .tabla-c(data-aos="fade-down-right")
      table
        tr
          td.fondo-9.anchocol1.text-center.borde-der
            .h4 No.1
          td.fondo-9.anchocol1.text-center.borde-der
            .h4 Peso crisol (g)
          td.fondo-9.anchocol1.text-center.borde-der
            .h4 Peso crisol + muestra (g)
          td.fondo-9.anchocol1.text-center.borde-der
            .h4 Peso neto residuos (g)
          td.fondo-9.anchocol1.text-center.borde-der
            .h4 Peso crisol + cenizas (g)
          td.fondo-15.anchocol1.text-center.borde-der
            .h4 Peso neto cenizas (cenizas - crisol)(g) (Residuos - peso Crisol)
          td.fondo-16.anchocol1.text-center
            .h4 Porcentaje de cenizas (%)
        tr
          th.anchocol1.text-center.borde-der 1
          td.anchocol1.borde-der
          td.anchocol1.borde-der
          td.anchocol1.borde-der
          td.anchocol1.borde-der 
          td.anchocol1.borde-der 
          td.anchocol1
    p.my-5(data-aos="fade-down-left") Hasta este punto, usted ha estudiado 6 acciones para desarrollar muestreo de sólidos en el laboratorio. Para completar el estudio de los elementos de caracterización y muestreo de los residuos sólidos. Desarrolle la actividad que se propone a continuación; allí encontrará otras acciones para llevar a cabo ese proceso.
    //--Título fondo azul
    .row.my-5
      .col-auto(data-aos="fade-down-left")
        h3.text-white.text-center.fondo-4 Cálculo para la determinación del porcentaje de cenizas
    .row.justify-content-center
      .col-lg-4.col-md-12.mb-4(data-aos="fade-down-right")
        p Donde: 
        p.mb-0 CC = Peso del crisol más la ceniza (g) 
        p.mb-0 W = Peso del crisol vacío (g) 
        p.mb-0 CS = Peso del crisol con la muestra seca (g)
      .col-lg-4.col-md-12(data-aos="fade-down-left")
        img(src='@/assets/curso/tema10/ecuacion2.svg')
    //--Título fondo azul
    .row.my-5
      .col-auto(data-aos="fade-down-left")
        h3.text-white.text-center.fondo-4 Determinación de pH
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema10/imagen8.jpg')})`}"
      )
      .bloque-texto-g__texto.px-4.py-5
        p El pH puede definirse como una medida que expresa el grado de acidez o basicidad. El valor de pH representa el menos logaritmo en base diez de la concentración (actividad) de iones hidrógeno [H+ ]. Como la escala es logarítmica, la caída en una unidad de pH es equivalente a un aumento de 10 veces en la concentración de H+ . Entonces, una muestra de agua con un pH de 5 tiene 10 veces más H+ que una de pH 6 y 100 veces más que una de pH 7.
    //--Título fondo azul
    .row.my-5
      .col-auto(data-aos="fade-down-left")
        h3.text-white.text-center.fondo-4 Procedimiento en el laboratorio
    .row.justify-content-center
      .col-lg-7.col-md-12(data-aos="fade-down-right")
        p Según determinación de pH (2007):
        p El pH puede ser analizado en el campo o en el laboratorio. No olvide utilizar recipientes bien limpios para tomar y acarrear las muestras de suelo (preferentemente lávalas previamente y enjuáguese con agua destilada) Si la muestra es llevada al laboratorio, la determinación debe ser realizada preferentemente dentro de las 2 primeras horas a partir de la colecta, ya que puede cambiar por interacción con el anhídrido carbónico (CO2) atmosférico. Conserve las muestras refrigeradas para su transporte. (como se ya se indicó)
        p La determinación será realizada con tiras indicadoras. Estas simplemente se sumergen por un instante en la muestra de agua, lo que provoca un cambio de color. Posteriormente se comparan con el patrón de coloración impreso en la caja para asignarles un pH. (p.2)
      .col-lg-5.col-md-12(data-aos="fade-down-left")
        img(src='@/assets/curso/tema10/imagen9.jpg')
    p.mt-5(data-aos="fade-down-right") El otro procedimiento se basa en colocar la muestra en un vaso de precipitado, introducir el electrodo del potenciómetro y realizar la lectura.
    //--Título fondo azul
    .row.mt-5.mb-4
      .col-auto(data-aos="fade-down-left")
        h3.text-white.text-center.fondo-4 Densidad
    p(data-aos="fade-down-right") De acuerdo al Ministerio de Medio Ambiente Perú (2014):
    p(data-aos="fade-down-right") La densidad hace referencia a la cantidad de masa ocupada en un volumen determinado y su relación es referenciada al peso: g/mL; kg/m3 …etc. 
    p.mb-5(data-aos="fade-down-right") Para la determinación se realiza el siguiente protocolo.
    //-.row.justify-content-center.align-items-center.my-5
      .col-lg-5.col-sm-12(data-aos="fade-down-left")
        img(src='@/assets/curso/tema10/imagen10.jpg')

    .row.mb-3.fondo-11.redondearpuntas.align-items-center.p-3.justify-content-center
      .col-lg-1.col-md-2.col-sm-2.col-3.mb-4.mb-sm-0(data-aos="fade-down-right")
        img(src='@/assets/curso/tema5/1.svg')
      .col-lg-11.col-md-10.col-sm-10.col-12(data-aos="fade-down-left")
        p Utilizar un recipiente con capacidad conocida de preferencia cilindros 150 u 200 litros y con lados homogéneos.
    .row.mb-3.fondo-11.redondearpuntas.align-items-center.p-3.justify-content-center
      .col-lg-1.col-md-2.col-sm-2.col-3.mb-4.mb-sm-0(data-aos="fade-down-right")
        img(src='@/assets/curso/tema5/2.svg')
      .col-lg-11.col-md-10.col-sm-10.col-12(data-aos="fade-down-left")
        p Medir la altura y diámetro del recipiente cilíndrico.
    .row.mb-3.fondo-11.redondearpuntas.align-items-center.p-3.justify-content-center
      .col-lg-1.col-md-2.col-sm-2.col-3.mb-4.mb-sm-0(data-aos="fade-down-left")
        img(src='@/assets/curso/tema5/3.svg')
      .col-lg-11.col-md-10.col-sm-10.col-12(data-aos="fade-down-right")
        p Al azar escoger bolsas de las ya registradas y pesadas y vaciar su contenido dentro del recipiente.
    .row.mb-3.fondo-11.redondearpuntas.align-items-center.p-3.justify-content-center
      .col-lg-1.col-md-2.col-sm-2.col-3.mb-4.mb-sm-0(data-aos="fade-down-right")
        img(src='@/assets/curso/tema5/4.svg')
      .col-lg-11.col-md-10.col-sm-10.col-12(data-aos="fade-down-left")
        p Una vez lleno el recipiente, levantar el cilindro 20 cm sobre la superficie y dejarlo caer, repite esta acción por tres veces, con la finalidad de uniformizar la muestra llenando los espacios vacíos del cilindro.
    .row.mb-3.fondo-11.redondearpuntas.align-items-center.p-3.justify-content-center
      .col-lg-1.col-md-2.col-sm-2.col-3.mb-4.mb-sm-0(data-aos="fade-down-left")
        img(src='@/assets/curso/tema5/5.svg')
      .col-lg-11.col-md-10.col-sm-10.col-12(data-aos="fade-down-right")
        p Medir la altura y registrar el dato.
    .row.mb-3.fondo-11.redondearpuntas.align-items-center.p-3.justify-content-center
      .col-lg-1.col-md-2.col-sm-2.col-3.mb-4.mb-sm-0(data-aos="fade-down-right")
        img(src='@/assets/curso/tema10/6.svg')
      .col-lg-11.col-md-10.col-sm-10.col-12(data-aos="fade-down-left")
        p Realizar este procedimiento durante los 8 días del estudio.
    .row.mb-5.fondo-11.redondearpuntas.align-items-center.p-3.justify-content-center
      .col-lg-1.col-md-2.col-sm-2.col-3.mb-4.mb-sm-0(data-aos="fade-down-left")
        img(src='@/assets/curso/tema10/7.svg')
      .col-lg-11.col-md-10.col-sm-10.col-12(data-aos="fade-down-right")
        p Cuando se llene el cilindro se procede a determinar la altura que se deja libre de residuos sólidos dentro de este, para ello se debe medir la altura libre del cilindro es decir la altura sin residuos y se registra. (p.43).
    p.my-5.text-center(data-aos="fade-down-right") Fórmula para calcular la densidad
    .row.justify-content-center
      .col-lg-4.col-md-12.mb-4(data-aos="fade-down-right")
        p Donde: 
        p.mb-0 S = Densidad de los residuos sólidos (Kg/m3)
        p.mb-0 W = Peso de los residuos sólidos
        p.mb-0 V = Volumen del residuo sólido
        p.mb-0 D = Diámetro del cilindro
        p.mb-0 H = Altura total del cilindro
        p.mb-0 π = Constante (3.1416)
      .col-lg-4.col-md-12(data-aos="fade-down-left")
        img(src='@/assets/curso/tema10/ecuacion3.svg')
    //--Título fondo azul
    .row.my-5
      .col-auto(data-aos="fade-down-left")
        h3.text-white.text-center.fondo-4 Resistencia microbiológica
    p.mb-5(data-aos="fade-down-right") Es la capacidad que tienen los microorganismos de soportar los efectos de biocidas con la finalidad de eliminarlas o controlarlas.
    //--Título fondo azul
    .row.my-5
      .col-auto(data-aos="fade-down-left")
        h3.text-white.text-center.fondo-4 Materiales y métodos
    .row.justify-content-center
      .col-lg-7.col-md-12(data-aos="fade-down-right")
        p Según Mantilla, C. (2010): 
        p Con las muestras llevadas al laboratorio se elabora los medios cultivo líquidos a partir de los residuos-sólidos se realiza pesaje, picado y licuado en un volumen adecuado de agua destilada hasta obtener las concentraciones de 25, 50 y 75% p/v; el pH se ajusta a 6,70 con una solución de bicarbonato de sodio al 10%.
        p Para la preparación de los medios de cultivos sólidos se realiza el mismo procedimiento adicionando agar-agar en cantidad apropiada de acuerdo con el producto comercial (15 g/L).
        p Los medios preparados se esterilizan a 1 atm de presión, 121 °C, durante 15-20 min. (párr.8).
      .col-lg-5.col-md-12(data-aos="fade-down-left")
        img(src='@/assets/curso/tema10/imagen11.jpg')
    //--Título fondo azul
    .row.my-5
      .col-auto(data-aos="fade-down-left")
        h3.text-white.text-center.fondo-4 Relación carbono nitrógeno
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema10/imagen12.jpg')})`}"
      )
      .bloque-texto-g__texto.px-4.py-5
        p Es la relación que se presenta entre el carbono con respecto al nitrógeno en los residuos orgánicos, todos los residuos tienen relaciones distintas, por eso es importante mezclar diversos materiales para llegar a la relación adecuada. La relación con la que se han encontrado mejores resultados en el proceso de degradación de los residuos orgánicos es de 30/1 (30 carbonos por cada nitrógeno) en la mezcla final, cuando se mezclan materiales diversos puede que la relación no de exactamente este valor, pero sus valores deben estar en rangos cercanos.
        p La relación C/N tiene gran importancia, ya que ayuda a la descomposición de los residuos, evitando a la vez que se generen olores desagradables.
    p.mt-5(data-aos="fade-down-right") Habiendo estudiado con atención las acciones de muestreo de sólidos en el laboratorio, es momento de conocer la importancia del carbono.
    p(data-aos="fade-down-right") El carbono es la fuente de energía para los microorganismos; el carbono se puede encontrar en residuos con altos contenidos de carbohidratos, generalmente se asocian con materiales de color café o amarillo, entre estos están aserrín, hojarasca, cascarilla de arroz, paja, papel, etc.
    p.my-5.text-center(data-aos="fade-down-right") Según Casco E (2005):

    .tarjeta.tarjeta--gris.fondo-7.py-5.px-4.mb-5
      SlyderA(tipo="b")(data-aos="fade-down-left")
        .row.justify-content-center
          .col-md-4.mb-4.mb-md-0
            p De otra parte, la importancia del nitrógeno, se debe a que es un elemento importante en la estructura de las proteínas y se relaciona con la generación de microorganismos y a mayor cantidad de ellos más rápida la degradación de los residuos sólidos orgánicos.
          .col-md-7
            figure
              img(src='@/assets/curso/tema10/imagen13.png')
        .row.justify-content-center
          .col-md-4.mb-4.mb-md-0
            p Para garantizar una relación C/N adecuada es necesario mezclar en correctas proporciones residuos orgánicos ricos en C y ricos en N. Es deseable que la relación carbono nitrógeno (C/N) esté en el rango de 25 a 35/1 en la mezcla inicial.
          .col-md-7
            figure
              img(src='@/assets/curso/tema10/imagen14.png')
        .row.justify-content-center
          .col-md-4.mb-4.mb-md-0
            p Si el residuo tiene una alta relación C/N, pero la materia orgánica es poco biodegradable, la relación C/N disponible realmente para los microorganismos es menor y el proceso evolucionará rápidamente, pero afectará solo a una proporción de la masa total.
          .col-md-7
            figure
              img(src='@/assets/curso/tema10/imagen15.png')
        .row.justify-content-center
          .col-md-4.mb-4.mb-md-0(data-aos="fade-down-right")
            p Si la relación C/N es muy baja el compostaje es más rápido pero el exceso de nitrógeno se desprende en forma amoniacal, produciéndose una autorregulación de la relación C/N del proceso (<em>Dalzell</em> et al, 1991, Barrena, 2006 & Moreno y Moral, 2007).
          .col-md-7(data-aos="fade-down-left")
            figure
              img(src='@/assets/curso/tema10/imagen16.png')
        .row.justify-content-center
          .col-md-4.mb-4.mb-md-0(data-aos="fade-down-right")
            p Según Velástegui (2009), la cantidad de carbono necesaria es superior a la de nitrógeno, por dos razones fundamentales:
            p • Debido a que los microorganismos lo utilizan para la formación del material celular y como fuente de energía. 
            p • Porque está presente en el material celular en cantidad muy superior a la del nitrógeno, pero esta cantidad varía según el microorganismo. (p.48)
          .col-md-7(data-aos="fade-down-left")
            figure
              img(src='@/assets/curso/tema10/imagen17.png')
    separador
    #t_10_2.titulo-segundo.color-acento-contenido(data-aos="fade-down-right")
      h2 10.2 Equipos para análisis de muestras en residuos sólidos
    p.mb-5(data-aos="fade-down-right") En el desarrollo de este tema, conoceremos las características de los equipos de laboratorio y de campo para el análisis de residuos sólidos.
    //--Título fondo azul
    .row.my-5
      .col-auto(data-aos="fade-down-left")
        h3.text-white.text-center.fondo-4 Medición de humedad
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema10/imagen18.jpg')})`}"
      )
      .bloque-texto-g__texto.px-4.py-5
        p Para esta prueba se tiene un sensor de humedad, del cual, en el comercio existen diferentes tipos como los hidrómetros o sensores de humedad en el suelo, el cual permite medir la conductividad en el suelo y su funcionamiento se da por medio de dos microsensores, los cuales se ajustan a la humedad relativa de la zona dada, generando la información por medio de un proceso de conversión mediante un chip situado en el sistema del equipo.
    .row.justify-content-center.my-5
      .col-lg-7.col-md-12.mb-4(data-aos="fade-down-right")
        p Los sensores proporcionan las lecturas de los contenidos volumétricos de agua en la muestra a la que se colocan (m3 de agua/m3 de suelo) Estos sensores ya están precalibrados para usarse en una amplia gama de tipos de suelo o de muestras de residuos sólidos. Se deberán realizar algunas calibraciones. 
        p Otro procedimiento para la determinación de la humedad y por otra parte de las cenizas es en el laboratorio con el uso de la mufla y el horno, una vez llevadas las muestras al laboratorio, recuerde seguir los protocolos de cadena de custodia. 
        p Procure homogeneizar 100 g que se necesita de muestra para los análisis de laboratorio, con el fin de tener una muestra representativa. Posteriormente se realiza el picado de las muestras de cada categoría en pedazos no mayores a 1cm con la ayuda de la espátula de laboratorio para después trasladarlas a los crisoles de porcelana. 
        p Los crisoles deben estar previamente tarados, este procesos se lleva a cabo lavándose muy bien, luego colocarlos en el horno a 105 ªC por 40 min, posteriormente, con las pinzas para crisol llévalos al desecador para la absorción de la humedad que pueda tener el crisol , en el desecador debe pasar más o menos 20 min a 30 min.
      .col-lg-5.col-md-12(data-aos="fade-down-left")
        img(src='@/assets/curso/tema10/imagen19.jpg')
    p.mb-5(data-aos="fade-down-right") Pese los crisoles en una balanza analítica y registre los datos con las 5 cifras significativas, es recomendable realizar la prueba por triplicado.
    .tabla-c(data-aos="fade-up")
      table
        tr
          td.fondo-9.anchocol1.text-center.borde-der
            .h4 No.1
          td.fondo-9.anchocol1.text-center.borde-der
            .h4 Peso crisol (g)
          td.fondo-9.anchocol1.text-center.borde-der
            .h4 Peso crisol + muestra húmeda (g)
          td.fondo-9.anchocol1.text-center.borde-der
            .h4 Peso neto residuos (g)
          td.fondo-9.anchocol1.text-center.borde-der
            .h4 Peso crisol + Residuos secos (g)
          td.fondo-15.anchocol1.text-center.borde-der
            .h4 Peso neto residuos sin humedad (g) (Residuos - peso Crisol)
          td.fondo-16.anchocol1.text-center
            .h4 % Humedad total
        tr
          th.anchocol1.text-center.borde-der 1
          td.anchocol1.borde-der
          td.anchocol1.borde-der
          td.anchocol1.borde-der
          td.anchocol1.borde-der 
          td.anchocol1.borde-der 
          td.anchocol1 
    p.my-5(data-aos="fade-down-right") Posteriormente afore el crisol, pese nuevamente y registre el peso dado. Lleve los crisoles al horno a 105ªC por 24 horas, pasado el tiempo apague el horno y espere 10 min antes de abrir la compuerta. Lleve, con la ayuda de las pinzas, los crisoles al desecador esperen de 20 min a 25 min y pese nuevamente. 
    //--Título fondo azul
    .row.my-5
      .col-auto(data-aos="fade-down-left")
        h3.text-white.text-center.fondo-4 Determinación de cenizas
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema10/imagen20.jpg')})`}"
      )
      .bloque-texto-g__texto.px-4.py-5
        p Para la determinación de las cenizas se realiza el mismo procedimiento anterior, pero con ciertas diferencias, como, cuando afore los crisoles con las muestras, llévalas a la mufla, que previamente está  encendida a los 900 ºC. Debe tener mucha precaución utilizando las pinzas correspondientes, deje las muestras por 6 horas, pasado este tiempo, apague la mufla y espere 45 min a que se enfríe y con la ayuda de las pinzas lleve los crisoles al desecador y espere de 20 min a 25 min, pese de nuevo los crisoles con las muestras y registre. 
    //--Título fondo azul
    .row.my-5
      .col-auto(data-aos="fade-down")
        h3.text-white.text-center.fondo-4 pH
    p(data-aos="fade-down-right") Según Cuervo J (2014):
    p(data-aos="fade-down-left") La medición del parámetro de pH es de gran importancia, ya que permite determinar si los residuos sólidos tienen propiedades alcalinas o ácidas. Un factor a tener en cuenta es que algunas materias primas pueden aumentar el pH (residuos del procesado de papel, cenizas) y otras disminuirlo (residuos de comida). Por otro lado, la producción de ácidos orgánicos y las condiciones anaeróbicas (ausencia de aire) pueden producir pH < 4,5 limitando la actividad microbiana. (p.31).
    p(data-aos="fade-down-right") La medición de este parámetro se puede hacer mediante cintas de papel tornasol, esta es una tecnología de bajo costo, que puede ser utilizada por cualquier persona. El procedimiento para medir este parámetro es poner la cinta humedecida sobre los residuos o sobre el material ya degradado.
    .row.justify-content-center.my-5
      .col-lg-8.col-md-12(data-aos="fade-down-left")
        img(src='@/assets/curso/tema5/figura3.svg')
    p.text-center(data-aos="fade-down-right") Para procesos más tecnificados lo mejor es contar con un pH metro digital para suelos o residuos sólidos, que se introduce en la mezcla y da el valor de pH.
    .row.justify-content-center.mt-5
      .col-lg-10.col-md-12(data-aos="fade")
        img(src='@/assets/curso/tema10/imagen21.jpg')
</template>

<script>
export default {
  name: 'Tema10',
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
