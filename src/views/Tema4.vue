<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos="fade-down-right")
      .titulo-principal__numero.text-white
        span 4
      h1 Protocolos para análisis de agua, suelo, olores y residuos sólidos
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema4/imagen1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p La importancia que representa la calidad del agua, el suelo y la reducción de los malos olores emitidos por distintos tipos de fuentes es asegurado por los protocolos de análisis químicos, físicos y microbiológicos donde se identifica la información necesaria de los analitos en cuestión; para obtener datos de forma precisa y exacta de las características de la muestra analizada.
    p.my-5(data-aos="fade-down-left") Estos datos deben provenir de muestras representativas y análisis de acuerdo con protocolos que sigan estrictas normas técnicas y legales de control de calidad. Los análisis clásicos (volumétricos y gravimétricos) y las técnicas instrumentales de análisis cobran gran relevancia en el control y caracterización medioambiental; ofreciendo alternativas de solución a diversas  problemáticas que surgen de los las prácticas de uso del agua y el suelo y de los procesos industriales de los diversos sectores  de  mundo.
    separador
    #t_4_1.titulo-segundo.color-acento-contenido(data-aos="fade-down-right")
      h2 4.1 Parámetros de análisis físicos, químicos y microbiológicos el agua
    .row.justify-content-center
      .col-lg-7.col-md-12(data-aos="fade-down-right")
        p La calidad del agua superficial es una de las condiciones ambientales más importantes en el monitoreo actual del país y el mundo; la calidad del agua depende tanto de factores naturales, como de la acción humana, y se determina comparando las características físicas y químicas de una muestra de agua, con unas directrices legales de calidad del agua o estándares técnicos.
        .row.justify-content-center.align-items-center.fondo-5.ps-3.pe-5.py-4.redondearpuntas.mb-4
          .col-md-2.col-sm-3.col-4
            img(src='@/assets/curso/tema4/descargar-pdf.svg')
          .col-xxl-8.col-md-7.text-white
            h3.mb-0 Parámetros análisis del agua
            p.text-small.mb-4.mb-md-0 Conozca los Parámetros de análisis físico, químico y microbiológico del agua.
          .col-xxl-2.col-md-3
            a.boton.color-acento-botones(:href="obtenerLink('downloads/Parametros_analisis_del_agua.pdf')" target="_blank" type="application/pdf")
              span Descargar
              i.fas.fa-file-download
      .col-lg-5.col-md-12(data-aos="fade-down-left")
        img(src='@/assets/curso/tema4/imagen2.png')
    separador
    #t_4_2.titulo-segundo.color-acento-contenido(data-aos="fade-down-right")
      h2 4.2 Parámetros de análisis físicos, químicos y microbiológicos del suelo
    .row.justify-content-center
      .col-lg-7.col-md-12(data-aos="fade-down-right")
        p La calidad del suelo ha sido definida por la Sociedad de Ciencias del Suelo de América, como “la capacidad de un tipo específico de suelo para funcionar, dentro de los límites de los ecosistemas naturales, para sostener la productividad vegetal y animal, mantener y/o mejorar la calidad del agua y del aire, y apoyar la salud y la vivienda”.
        .row.justify-content-center.align-items-center.fondo-5.ps-3.pe-5.py-4.redondearpuntas.mb-4
          .col-md-2.col-sm-3.col-4
            img(src='@/assets/curso/tema4/descargar-pdf.svg')
          .col-xxl-8.col-md-7.text-white
            h3.mb-0 Parámetros análisis del suelo
            p.text-small.mb-4.mb-md-0 Conozca los Parámetros de análisis físico, químico y microbiológico del suelo.
          .col-xxl-2.col-md-3
            a.boton.color-acento-botones(:href="obtenerLink('downloads/Parametros_analisis_del_suelo.pdf')" target="_blank" type="application/pdf")
              span Descargar
              i.fas.fa-file-download
      .col-lg-5.col-md-12(data-aos="fade-down-left")
        img(src='@/assets/curso/tema4/imagen3.png')
    separador
    #t_4_3.titulo-segundo.color-acento-contenido(data-aos="fade-down-right")
      h2 4.3 Parámetros de análisis físicos, químicos y microbiológicos del olor
    p.mb-5(data-aos="fade-down-left") Al hablar de calidad del aire atmosférico se debe recurrir, a la siguiente normatividad legal y técnica.
    h4.text-center(data-aos="fade-down-right") Normatividad legal y técnica para la calidad del aire atmosférico
    .row.justify-content-center
      .col-8(data-aos="fade-down-left")
        p.text-center Es momento de revisar la normatividad que rige los parámetros de análisis físicos, químicos y microbiológicos del olor. Presione cada uno de los botones que aparecen en pantalla y estúdielos atentamente.
    .row.justify-content-center
      .col-lg-6.col-md-8.col-sm-10.col-12(data-aos="fade-down-right")

        ImagenInfografica.color-acento-botones.mb-5
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/tema4/figura1.svg')

          .tarjeta.fondo-6.p-3(x="27%" y="53.5%" numero="+")
            .h5.mb-2  Resoluciones
            ul.lista-ul
              li 
                i.lista-ul__vineta.mb-0
                | Resolución 601 de 2006
              li 
                i.lista-ul__vineta.mb-0
                | Resolución 1541 de 2013
              li 
                i.lista-ul__vineta.mb-0
                | Resolución 672 de 2014
              li 
                i.lista-ul__vineta.mb-0
                | Resolución 1490 de 2014
              li 
                i.lista-ul__vineta
                | Resolución 2087 de 2014.

            p “Por la cual se establece la norma de calidad de aire o nivel de inmisión, para todo territorio nacional en condiciones de referencia”.

          .tarjeta.fondo-6.p-3(x="50%" y="14%" numero="+")
            .h5.mb-2 Normas técnicas colombianas
            ul.lista-ul
              li 
                i.lista-ul__vineta.mb-0
                | NTC 5880
              li 
                i.lista-ul__vineta.mb-0
                | NTC 6011
              li 
                i.lista-ul__vineta.mb-0
                | NTC 6012 - 1

            p Calidad del aire. Determinación de la concentración de olor por olfatometría dinámica.

          .tarjeta.fondo-6.p-3(x="72%" y="54%" numero="+")
            .h5.mb-2 Normas internacionales
            ul.lista-ul
              li 
                i.lista-ul__vineta.mb-0
                | Norma Europea UNE EN 13725 de 2004
              li 
                i.lista-ul__vineta.mb-0
                | Norma Chilena NCh 3190 de 2010
              li 
                i.lista-ul__vineta.mb-0
                | Norma Alemana VDI 3880 de 2011
              li 
                i.lista-ul__vineta.mb-0
                | Norma Alemana VDI 3884 de 2015

            p Citado de: tqi.co (s, f). Soluciones-confiables-olfatometría
            p https://tqi.co/soluciones-confiables/olfatometria/#
          .tarjeta.fondo-6.p-3(x="50%" y="85%" numero="+")
            .h5.mb-2 Norma UNE-EN 13725: 2004
            p Según la norma UNE-EN 13725: 2004 “Calidad del aire. Determinación de la concentración de olor por olfatometría dinámica”, define el olor como “la propiedad organoléptica perceptible por el órgano olfativo cuando inspira sustancias volátiles”. Esta norma desarrolla las cuestiones relacionadas con la toma de muestras, cuantificación de la concentración de olor y cálculo de la emisión de olor de los focos.
    p.my-5(data-aos="fade-down-left") Para afianzar más y mejor los parámetros físicos, químicos y microbiológicos del olor, le presentamos algunos elementos conceptuales y técnicos, adicionales, de suma importancia.
    h4.text-center(data-aos="fade-down-right") Parámetros de análisis físicos, químicos y microbiológicos del olor:
    p.mb-5(data-aos="fade-down-left") El olor es una reacción sensorial de determinadas células situadas en la cavidad nasal. La relación entre olor y molestia percibida es compleja de definir. En esa confluyen factores físicos y químicos fáciles de determinar, pero también otros de carácter subjetivo más difícil de evaluar, como, por ejemplo, el carácter agradable o desagradable del olor (tono hedónico), la sensibilidad de cada persona, o el entorno en el que es percibido.
    .row.justify-content-center
      .col-lg-8.col-md-12(data-aos="fade-down-right")
        TabsA.color-acento-botones.mb-5

          .tarjeta.fondo-7.p-4(titulo="Regulación Ambiental")
            h4 Regulación Ambiental
            p En los últimos años, la regulación ambiental ha aumentado significativamente, en paralelo a una sociedad más participativa y dotada de una mayor concienciación ambiental, que reclama la intervención de las administraciones públicas con el objetivo de garantizar el bienestar y la calidad de vida.

          .tarjeta.fondo-7.p-4(titulo="Contaminación Ambiental")
            h4 Contaminación Ambiental
            p Los malos olores causados por actividades tales como explotaciones de ganado, actividades industriales, depuradoras, vertederos, etc., se entienden como un tipo de contaminación ambiental debido a que, aunque los olores no lleguen a ser tóxicos, pueden llegar a provocar malestar, molestias respiratorias, alteraciones psicológicas.
          
          .tarjeta.fondo-7.p-4(titulo="Los olores y la salud pública")
            h4 Los olores y la salud pública
            p Al ser los olores un factor para la aceptación o rechazo, la población puede llegar a percibir los olores como un peligro para su salud, ocasionando niveles de descontento tan negativos como cualquier otro problema ambiental. Los problemas derivados de las molestias a la población de las actividades generadoras de los olores son difíciles de abordar por cuestiones de vacío legal o técnicas ya que por el momento no existe en nuestro país legislación estatal que regule o limite las emisiones de olor.

          .tarjeta.fondo-7.p-4(titulo="Origenes")
            h4 Origenes
            p El olor puede tener varios orígenes en función de la fuente que lo genere. Esto implica que la forma de tratar las molestias asociadas se debe abordar de distintas formas. Se debe tener en consideración que la afectación sobre el entorno varía y tiene unas características específicas según el tipo de procedencia.

          .tarjeta.fondo-7.p-4(titulo="Episodios de Olor")
            h4 Episodios de Olor
            p Así, por ejemplo, se pueden producir desde situaciones en las que existan áreas extensas afectadas hasta fenómenos puntuales, tanto en el ámbito espacial como temporal. Es decir, que es necesario tener en cuenta que puede haber muchos tipos de episodios de olor: baja intensidad, pero larga duración, alta intensidad y corta duración, puntuales a lo largo de un período de tiempo, o de una alta frecuencia temporal. Este hecho obliga a objetivar la molestia ofreciendo unas garantías tanto al ciudadano como a las instalaciones generadoras de olor.

          .tarjeta.fondo-7.p-4(titulo="Olfatometría")
            h4 Olfatometría
            p La olfatometría es una técnica de toma de muestras y análisis de olores que, unida al desarrollo de sistemas de modelización de la dispersión, permite evaluar las molestias producidas por malos olores y determinar el origen de las mismas.
      .col-lg-4.col-md-12.mb-4(data-aos="fade-down-left")
        img(src='@/assets/curso/tema4/imagen4.svg')
    .row.fondo-8.p-4.align-items-center.justify-content-center
      .col-lg-1.col-md-2.col-sm-2.col-4.mb-4(data-aos="fade-down-right")
        img(src='@/assets/curso/tema4/alerta.svg')
      .col-lg-11.col-md-10.col-sm-10.col-12(data-aos="fade-down-left")
        p Los estudios olfato métricos constituyen una herramienta de gran utilidad para el control y reducción de los malos olores emitidos por distinto tipo de fuentes. Estos estudios permiten no sólo determinar el grado de molestia creado en el entorno, sino también identificar las fuentes de olor realmente importantes y adoptar sistemas eficaces de eliminación.
        p.mb-0 Citado de: Asociación Española para la calidad AEC (2010) Contaminación Odorífera  p.1-2
        p.mb-0 https://www.aec.es/c/document_library/get_file?uuid=3527643c-0525-42fd-9943-1c881254e44f&groupId=10128
    p.my-5(data-aos="fade-down-right") Es momento de adentrarse en las Técnicas físico químicas de análisis olfatométricos. La caracterización de los olores se puede realizar mediante dos técnicas esencialmente: sensoriales y analíticas.
    .row.mb-5
      .col-auto(data-aos="fade-down-left")
        h3.text-white.text-center.fondo-4 a. Técnicas sensoriales
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema4/imagen5.jpg')})`}"
      )
      .bloque-texto-g__texto.px-4.paddy
        p Se basan en la percepción de los olores por el olfato humano. También incluyen la determinación del carácter de un olor (mapeo) y el nivel de agrado o desagrado de un olor (tono hedónico). Las técnicas sensoriales utilizan asesores humanos para medir un olor, siendo la olfatometría, la técnica usada comúnmente.
    p.my-5(data-aos="fade-down-left") Dicha prueba evalúa las diluciones con aire limpio que un olor debe sufrir para no ser detectable por un humano promedio (umbral de detección).
    h3(data-aos="fade-down-right") Mapeo triangular
    p.mb-5(data-aos="fade-down-left") Otras técnicas sensoriales incluyen la determinación del carácter de un olor (mapeo triangular) y el nivel de agrado o desagrado de un olor (tono hedónico) Las técnicas sensoriales tienen la ventaja de que proveen información útil sobre cómo las personas perciben los olores y el grado de molestia que provoca un olor determinado, o bien para evaluar la efectividad de un equipo de control de olores. La desventaja de este método es que no es específico y consecuentemente no identifica las especies químicas causantes del olor. Dentro de las técnicas sensoriales tenemos:
    AcordionA(data-aos="fade-down-right").mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
      .row.justify-content-center(titulo="Olfatometría dinámica")
        .col-md-2.col-sm-4.col-5.mb-4.mb-md-0
          figure
            img(src='@/assets/curso/tema4/figura2.svg')
        .col-md-9.col-sm-12.col-12.mb-4.mb-md-0
          p La norma UNE-EN 13725:2004 establece un marco normativo de regulación para la toma de muestras y ensayo por olfatometría dinámica, en los que se utiliza el olfato humano como sensor. Esta norma define una metodología para la determinación de la concentración de olor de una muestra gaseosa usando un panel de “evaluadores” humanos (panelistas) como sensor, así como la determinación de la emisión.
      .row.justify-content-center(titulo="Interpretación de Valores")
        .col-md-2.col-sm-4.col-5.mb-4.mb-md-0
          figure
            img(src='@/assets/curso/tema4/figura3.svg')
        .col-md-9.col-sm-12.col-12.mb-4.mb-md-0
          p Según Monteiro T (2012):
          p El objetivo primordial de un estudio olfatométricos es evaluar si las emisiones de una determinada instalación pueden ser responsables o no de quejas en la población vecina.
          p A esta conclusión se llega con la interpretación de los valores de concentración de inmisión, habitualmente denominados mapas de olores. (pp.51-52).
    .row.mb-5
      .col-auto(data-aos="fade-down-left")
        h3.text-white.text-center.fondo-4 b. Técnicas analíticas 
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-down")
      .bloque-texto-g__img.cambioimg(
        :style="{'background-image': `url(${require('@/assets/curso/tema4/imagen6.jpg')})`}"
      )
      .bloque-texto-g__texto.cambiotexto.p-4
        p Son métodos tradicionales de análisis químico para medir la concentración de compuestos específicos presentes en un olor. Puede hacerse mediante cromatografía de gases y espectrometría de masas, mediante métodos húmedos (para mercaptanos) mediante narices electrónicas o mediante indicadores.
        p Las técnicas analíticas para caracterización de olores son relativamente fáciles de aplicar e identificar cuantitativamente las especies químicas presentes en un olor. La desventaja de la técnica es que no provee información alguna referente a la molestia que puede generar un olor.
    p.mt-5(data-aos="fade-down-right") La contribución de las especies químicas aisladas puede sumarse para obtener la concentración global del olor. La presencia o ausencia de una especie química en la mezcla de gases, o las concentraciones de éstas pueden potenciar, disminuir o inclusive cambiar la percepción de un olor por completo.
    p.mb-5(data-aos="fade-down-left")  Debido a esto, las técnicas analíticas son usadas para definir criterios de diseño de métodos de control de olores, para determinar si las emisiones de una sustancia química específica están dentro de los niveles permitidos por las normas o para estimar la relación entre la concentración de una sustancia química y su equivalente en términos de percepción humana.
    AcordionA(data-aos="fade-down-right").mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
      .row.justify-content-center(titulo="Narices electrónicas")
        .col-lg-2.col-md-4.col-sm-4.col-5.mb-4.mb-lg-0
          figure
            img(src='@/assets/curso/tema4/imagen7.jpg')
        .col-lg-9.col-md-12.col-sm-12.col-12.mb-4.mb-lg-0
          p Las narices electrónicas son una serie de sensores de distintos materiales metálicos que reaccionan de forma distinta a un mismo componente químico.
          p Cuando una muestra olorosa entra en contacto con estos, se produce una respuesta química que se evalúa de forma conjunta para la totalidad de los sensores. La respuesta se relaciona con la intensidad o concentración del olor a partir de los valores obtenidos por panelistas humanos que trasladan los resultados a una base de datos que queda registrada.
      .row.justify-content-center(titulo="Espectrometría infrarroja")
        .col-lg-2.col-md-4.col-sm-4.col-5.mb-4.mb-lg-0
          figure
            img(src='@/assets/curso/tema4/imagen8.jpg')
        .col-lg-9.col-md-12.col-sm-12.col-12.mb-4.mb-lg-0
          p Los análisis químicos son métodos de investigación y tienen la ventaja de ser repetibles y seguros, y se usan para caracterizar los componentes químicos de episodios de olor, especialmente para compuestos desconocidos. Sin embargo, una muestra puntual para un periodo de tiempo con análisis químicos subsecuentes, provee sólo información integrada de tiempo, pero no información relacionada con la frecuencia, intensidad y duración de la exposición, la cual es requerida para identificar efectivamente la huella de los componentes del olor. 
          p En décadas anteriores se han desarrollado mejores tecnologías para análisis de compuestos químicos, como el espectrómetro transformador infrarrojo de paso abierto de Fourier (Open-Path Fourier transforminfrared / OP-FTIR) el cual ofrece monitoreo remoto, análisis multicompuestos rápidos y mediciones promedio.
      .row.justify-content-center(titulo="Cromatografía de gases-olfatometría, o GCO")
        .col-lg-2.col-md-4.col-sm-4.col-5.mb-4.mb-lg-0
          figure
            img(src='@/assets/curso/tema4/imagen9.jpg')
        .col-lg-9.col-md-12.col-sm-12.col-12.mb-4.mb-lg-0
          p La cromatografía de gases-olfatometría, o GCO, consiste en evaluar con la nariz humana las cualidades aromáticas de los compuestos que eluyen de la columna cromatográfica, a la vez que el detector instrumental instalado proporciona un cromatograma.
          p De esta manera se pueden asignar olores a los picos y/o determinarse a qué tiempos de retención se detectan olores. Así, tal y como puede verse en la siguiente figura, la detección olfatométrica y la instrumental son simultáneas, lo que permite relacionar la información sensorial con la información química.
    p.my-5(data-aos="fade-down-left") En la siguiente tabla se enuncian algunos procedimientos para la determinación de la concentración de sustancias de olores ofensivos en calidad del aire o inmisión:
    .titulo-sexto.color-acento-contenido(data-aos="fade-down")
      h5 Tabla 1. 
      span Elementos para la determinación de la concentración de sustancias de olores ofensivos en calidad del aire o inmisión
    .tabla-c(data-aos="fade-up")
      table
        caption.fondogris Citado de: fenavi.org. (2014). Resolución-2087-de-2014-Protocolo-Monitoreo-control-y-Vigilancia-de-Olores-Ofensivos-1.pdf. Colombia.p.9
          p https://fenavi.org/wp-content/uploads/2018/05/Resoluci%C3%B3n-2087-de-2014-Protocolo-Monitoreo-control-y-Vigilancia-de-Olores-Ofensivos-1.pdf
        tr.fondo-9
          <td colspan="2" class="text-center"><h4>Elementos para la determinación de la concentración de sustancias de olores ofensivos en calidad del aire o inmisión</h4></td>
        tr
          <td rowspan="5" class="text-center anchocol">
            <h5>Sustancia Evaluación analítica</h5> 
            <h5>Sulfuro de hidrógeno (H2S)</h5></td>
          td 
            p.mb-0 Sustancia Evaluación analítica.
        tr
          td 
            p.mb-0 Método automático. Determinación de los niveles de sulfuro de hidrogeno y TRS en el aire por fluorescencia UV.
        tr
          td 
            p.mb-0 Método 701. Determinación de sulfuro de hidrógeno en la atmósfera.
        tr
          td 
            p.mb-0 Métodos de muestreo y análisis de aire, 3a edición.
        tr
          td 
            p.mb-0 Método MFC/FD/FPD. Determinación de las emisiones de azufre.
        tr
          td.anchocol 
            h5.text-center Azufre total reducido (TRS)
          td 
            p.mb-0 Azufre total reducido Método automático. Determinación de los niveles de sulfuro de hidrogeno y TRS en el aire por fluorescencia UV.
        tr
          <td rowspan="4" class="text-center anchocol">
            <h5>Amoniaco (NH3)</h5>
          </td>
          td 
            p.mb-0 Método 401. Determinación de amoniaco en la atmósfera - Método del indofenol. Métodos de muestreo y análisis de aire, 3a edición.
        tr
          td 
            p.mb-0 Método Automático. Determinación de amoniaco en la atmósfera.
        tr
          td 
            p.mb-0 Método trampas de ácido. Determinación de las concentraciones de amoniaco en aire por trampas de ácido.
        tr
          td 
            p.mb-0 Método Denuders. Medición de amoniaco por muestreo denuder anular con análisis en línea.
    separador
    #t_4_4.titulo-segundo.color-acento-contenido(data-aos="fade-down-right")
      h2 4.4 Parámetros de análisis físicos y químicos de los residuos sólidos
    p.mb-5(data-aos="fade-down-right") Entre los diversos temas que guardan relación con una problemática de tanta actualidad como la protección y conservación del medio ambiente, la gestión de residuos sólidos ocupa un lugar principal dentro de la gestión ambiental. Esta gestión integrada es el término aplicado a todas las actividades asociadas con el manejo de los diversos flujos de residuos dentro de la industria y sociedad.
    h4.mb-5(data-aos="fade-down-left") Caracterización física y peso específico

    SlyderA.fondo-7.px-5.py-4(data-aos="fade-down-right").redondearpuntas(tipo="b")
      .row
        .col-lg-5.col-md-12.mb-4.mb-lg-0
          span.text-bold Caracterización física: 
          span Las características físicas más importantes de los residuos sólidos incluyen: peso específico o, contenido de humedad, tamaño de partícula y distribución del tamaño, capacidad de campo y porosidad de los residuos compactados.
          br
          br
          span.text-bold Peso específico: 
          span El peso específico se define como el peso de un material por unidad de volumen (por ejemplo, kg/m3) Como el peso específico de los RS frecuentemente se refiere a residuos sueltos, encontrados en los contenedores, no compactados, compactados, etc., la base utilizada para los valores presentados siempre debe ser citada. Los datos sobre el peso específico a menudo son necesarios para valorar la masa y el volumen total de los residuos que tienen que ser gestionados.
        .col-lg-7.col-md-12
          figure
            img(src='@/assets/curso/tema4/imagen10.png')

      .row
        .col-lg-5.col-md-12.mb-4.mb-lg-0
          h5 Contenido de humedad
          span.text-bold M= (w-d) X 100 
          span donde:
          p.mb-0 M= Contenido de humedad, porcentaje.
          p.mb-0 w= Peso inicial de la muestra según se entrega (kg)
          p.mb-0 d= Peso de la muestra después de secarse a 105 ºC (kg)
          p El contenido de humedad de los residuos sólidos normalmente se expresa de dos formas. En el método de medición peso-húmedo, la humedad de una muestra se expresa como un porcentaje del peso del material húmedo; en el método peso-seco, se expresa como un porcentaje del peso seco del material. El método peso-húmedo se usa más frecuentemente en el campo de la gestión de residuos sólidos. En forma de ecuación, el contenido de humedad peso-húmedo se expresa de la siguiente forma: 
            span.text-bold M= (w-d) X 100
        .col-lg-7.col-md-12
          figure
            img(src='@/assets/curso/tema4/imagen11.png')

      .row
        .col-lg-5.col-md-12.mb-4.mb-lg-0
          h5 Tamaño de partícula y distribución del tamaño
          p El tamaño y la distribución del tamaño de los componentes de los materiales en los residuos sólidos son una consideración importante dentro de la recuperación de materiales, especialmente con medios mecánicos, como cribas, tromeles y separadores magnéticos. El tamaño de un componente puede definirse mediante una de las siguientes medidas (imagen):
          p donde:
          p.mb-0 M = Contenido de humedad, porcentaje.
          p.mb-0 w = Peso inicial de la muestra según se entrega (kg) 
          p.mb-0 d = Peso de la muestra después de secarse a 105 ºC (kg)
        .col-lg-7.col-md-12
          figure
            img(src='@/assets/curso/tema4/imagen12.png')

      .row
        .col-lg-5.col-md-12.mb-3.mb-lg-0
          h5 Capacidad de campo
          p La capacidad de campo de los residuos sólidos es la cantidad total de humedad que puede ser retenida por una muestra de residuo sometida a la acción de la gravedad. La capacidad de campo de los residuos es de una importancia crítica para determinar la formación de la lixiviación en los vertederos. El exceso de agua sobre la capacidad de campo se emitirá en forma de lixiviación.
          p La capacidad de campo varía con el grado de presión aplicada y el estado de descomposición del residuo. Una capacidad de campo de un 30 por 100 en volumen se corresponde con 76,2 cm/256 cm. La capacidad de campo de los residuos no seleccionados y no compactados de orígenes domésticos y comerciales está en la gama del 50 al 60 por 100.
        .col-lg-7.col-md-12
          figure
            img(src='@/assets/curso/tema4/imagen13.png')

      .row
        .col-lg-5.col-md-12.mb-4.mb-lg-0
          h5 Permeabilidad de los residuos compactados
          p La conductividad hidrológica de los residuos compactados es una propiedad física importante que, en gran parte, gobierna el movimiento de líquidos y gases dentro de un vertedero. El coeficiente de permeabilidad normalmente se escribe como la imagen a continuación, donde:
          p.mb-0 K = Coeficiente de permeabilidad.
          p.mb-0 C = Constante sin dimensiones o factor de forma.
          p.mb-0 d = Tamaño medio de los poros.
          p.mb-0 y = Peso específico del agua.
          p.mb-0 µ = Viscosidad dinámica del agua.
          p.mb-0 K = Permeabilidad intrínseca.
        .col-lg-7.col-md-12
          figure
            img(src='@/assets/curso/tema4/imagen14.png')

      .row
        .col-lg-5.col-md-12.mb-4.mb-lg-0
          h5 Caracterización fisicoquímica
          p La información sobre la composición química de los componentes que conforman los RS es importante para evaluar las opciones de procesamiento y recuperación. Por ejemplo, la viabilidad de la incineración depende de la composición química de los residuos sólidos. Normalmente, se puede pensar que los residuos son una combinación de materiales semihúmedos combustibles y no combustibles. Si los residuos sólidos van a utilizarse como combustible, las cuatro propiedades más importantes que es preciso conocer son de acuerdo a Propiedades físicas, químicas y biológicas de los residuos sólidos urbanos capítulo 4:
        .col-lg-7.col-md-12
          figure
            img(src='@/assets/curso/tema4/imagen15.png')

      .row
        .col-lg-5.col-md-12.mb-4.mb-lg-0
          h5 Caracterización fisicoquímica
          ul.lista-ul
            li 
              i.fas.fa-check
              | Humedad (pérdida de humedad cuando se calienta a 105 ºC durante una hora).
            li 
              i.fas.fa-check
              | Materia volátil combustible (pérdida de peso adicional con la ignición a 950 ºC en un crisol cubierto).
            li 
              i.fas.fa-check
              | Carbono fijo (rechazo combustible dejado después de retirar la materia volátil).
            li 
              i.fas.fa-check
              | Ceniza (peso del rechazo después de la incineración en un crisol abierto). (pp.4-5).
        .col-lg-7.col-md-12
          figure
            img(src='@/assets/curso/tema4/imagen16.png')
</template>

<script>
export default {
  name: 'Tema4',
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
