<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Ciclo de vida del <i>software</i>
    p(data-aos="fade-down").mb-5 También conocido como (SDLC o Systems Development Life Cycle), es el proceso que se sigue para construir y hacer evolucionar un determinado <i>software</i>. El ciclo de vida permite iniciar una serie de fases mediante las cuales se procede a la validación y al desarrollo del <i>software</i> garantizando que se cumplan los requisitos para la aplicación y verificación de los procedimientos de desarrollo; para ello, se utilizan métodos del ciclo del <i>software</i>, que indican distintos pasos a seguir para el desarrollo de un producto.

    .row.justify-content-center.align-items-center(data-aos="fade-down")
      .col-lg-10
        .bloque-texto-a.color-acento-contenido.p-4.p-md-5.mb-5 
          .row.m-0.align-items-center.justify-content-between
            .col-lg-4.mb-4.mb-lg-0
              h2.mb-0 Si bien existen diferentes ciclos de desarrollo de <i>software</i>, la normativa ISO/IEC/IEEE 12207:2017 establece que:
            .col-lg-8
              .bloque-texto-a__texto.p-4
                p [Es] un marco común para los procesos del ciclo de vida de los programas informáticos, con una terminología bien definida, a la que pueda remitirse la industria del <i>software</i>. <b>Contiene procesos, actividades y tareas aplicables durante la adquisición, el suministro, el desarrollo, el funcionamiento, el mantenimiento o la eliminación de sistemas, productos y servicios informáticos</b>. Estos procesos del ciclo de vida se llevan a cabo mediante la participación de los interesados, con el objetivo final de lograr la satisfacción del cliente (s.p.).   

    p(data-aos="fade-down").mb-5.text-center A continuación, se indican cuáles son los elementos que integran un ciclo de vida: 

    .row.mt-5(data-aos="fade-left")
      .col-12
        .row
          .col-2.col-lg-1.offset-1.align-self-center.justify-content-center
            img(src='@/assets/curso/temas/42.svg', alt='', style='margin-right: -100px').w-100
          .col-8.py-3.border-y
            .col-sm.mb-5.mb-sm-0.mt-2.mx-5
              .h5 Fases
              p.mt-3 Una fase es un conjunto de actividades relacionadas con un objetivo en el desarrollo del proyecto. Se construye agrupando tareas (actividades elementales) que pueden compartir un tramo determinado del tiempo de vida de un proyecto. La agrupación temporal de tareas impone requisitos temporales correspondientes a la asignación de recursos (humanos, financieros o materiales).
    .row.mt-0(data-aos="fade-right")
      .col-12
        .row
          .col-2.col-lg-1.offset-1.align-self-center.justify-content-center
            img(src='@/assets/curso/temas/43.svg', alt='', style='margin-right: -100px').w-100
          .col-8.py-3.border-bot
            .col-sm.mb-5.mb-sm-0.mt-2.mx-5
              .h5 Entregables
              p.mt-3 Son los productos intermedios que generan las fases. Pueden ser materiales o inmateriales (documentos, <i>software</i>). Los entregables permiten evaluar la marcha del proyecto mediante comprobaciones de su adecuación o no a los requisitos funcionales y de condiciones de realización previamente establecido.

    Separador 
    #t_2_1.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 2.1 Fases  

    p(data-aos="fade-down").mb-5 Las fases del modelo de ciclo del <i>software</i> son: planificación, análisis, diseño, implementación, pruebas y mantenimiento, las cuales se describen en la siguiente figura.
    .bg8.p-5
      SlyderB.mb-5(:datos="datosSlyder").mt-5

    Separador 
    #t_2_2.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 2.2   Paradigmas de los modelos de ciclo de vida del <i>software</i>

    .cajon-b.color-acento-contenido.mb-4.py-2
      .row.align-items-center.justify-content-center
        .col-auto.my-3
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/49.svg', alt='')  
        .col-10.my-3
          p(data-aos="fade-down") Con la finalidad de proporcionar una metodología común entre el cliente y la empresa de <i>software</i>, se utilizan los modelos de ciclos de vida o paradigmas de desarrollo de <i>software</i> para plasmar las etapas y la documentación necesaria, de manera que cada fase se valide antes de continuar con la siguiente.

          p(data-aos="fade-down") Un modelo de ciclo de vida de <i>software</i> es una vista de las actividades que ocurren durante el desarrollo de <i>software</i> e intenta determinar el orden de las etapas involucradas y los criterios de transición asociados entre estas.

    .row.align-items-center.justify-content-center.mb-4
      .col-lg-5.my-3
        img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/50.png', alt='')
      .col-lg-7.my-3
        p(data-aos="fade-down") Según la norma 1074 IEEE se define al ciclo de vida del <i>software</i> como:
        .bloque-texto-b.color-primario.p-4.mb-4
          .bloque-texto-b__texto
            i.fas.fa-quote-left
            h2.mb-0 una aproximación lógica a la adquisición, el suministro, el desarrollo, la explotación y el mantenimiento del <i>software</i>
            i.fas.fa-quote-right 
        .cajon.color-secundario.p-4(data-aos="flip-down")
          p(data-aos="fade-down") La ISO/IEC 12207 Information Technology / <i>software</i> Life Cycle Processes señala que es: 

          p(data-aos="fade-down").mb-0 Un marco de referencia que contiene los procesos, las actividades y las tareas involucradas en el desarrollo, la explotación y el mantenimiento de un producto de <i>software</i>, abarcando la vida del sistema desde la definición de los requisitos hasta la finalización de su uso (2008).        

    p(data-aos="fade-down").mb-5 Existen modelos preestablecidos con los cuales se pude elaborar un proyecto; a continuación, se mencionan los diferentes paradigmas de modelos de ciclo de vida para desarrollar <i>software</i>.  
    .row.mt-5(data-aos="fade-left")
      .col-12
        .row
          .col-2.col-lg-1.offset-1.align-self-center.justify-content-center
            img(src='@/assets/curso/temas/51.svg', alt='', style='margin-right: -100px').w-100
          .col-8.py-3.border-y
            .col-sm.mb-5.mb-sm-0.mt-2.mx-5
              .h5 Paradigma tradicional 
              p.mt-3 Los paradigmas tradicionales se identifican, fundamentalmente, por ser lineales, es decir se trata de completar cada proceso de principio a fin hasta que quede listo para avanzar a la segunda fase del ciclo del <i>software</i>.

              p Si bien es verdad que las metodologías actuales están basadas en lo que fueron los paradigmas tradicionales, hoy en día se ha evolucionado, sin embargo, los paradigmas tradicionales se mantienen.
 
    .row.mt-0(data-aos="fade-right")
      .col-12
        .row
          .col-2.col-lg-1.offset-1.align-self-center.justify-content-center
            img(src='@/assets/curso/temas/52.svg', alt='', style='margin-right: -100px').w-100
          .col-8.py-3.border-bot
            .col-sm.mb-5.mb-sm-0.mt-2.mx-5
              .h5 Desventaja: 
              p.mt-3 Pérdida de tiempo si se encuentran errores en una fase avanzada porque al devolverse se debe pasar nuevamente por todas las fases y reestructurar de acuerdo con las modificaciones. 

    .row.mt-0(data-aos="fade-left")
      .col-12
        .row
          .col-2.col-lg-1.offset-1.align-self-center.justify-content-center
            img(src='@/assets/curso/temas/53.svg', alt='', style='margin-right: -100px').w-100
          .col-8.py-3.border-bot
            .col-sm.mb-5.mb-sm-0.mt-2.mx-5
              .h5 Paradigma orientado a objetos: 
              p.mt-3 Las etapas de desarrollo de <i>software</i> en el paradigma orientado a objetos, se conforma principalmente por la creación de clases, análisis de requisitos y el diseño. Con este paradigma se pretende que el código fuente sea reutilizable para otros proyectos.  

    .row.mt-0(data-aos="fade-right")
      .col-12
        .row
          .col-2.col-lg-1.offset-1.align-self-center.justify-content-center
            img(src='@/assets/curso/temas/54.svg', alt='', style='margin-right: -100px').w-100
          .col-8.py-3.border-bot
            .col-sm.mb-5.mb-sm-0.mt-2.mx-5
              .h5 Paradigma de desarrollo ágil 
              p.mt-3 El objetivo de este paradigma es el desarrollo de proyectos en poco tiempo, se simplifican procesos tediosos, se agilizan las fases del desarrollo y las interacciones se hacen en corto tiempo.

              p Una de las principales diferencias con los paradigmas anteriores es que el cliente se ve involucrado en el proyecto durante el desarrollo de este, así, el cliente sugiere mejoras, propone ideas y se mantiene al tanto del desarrollo del producto, a diferencia del paradigma tradicional y el orientado objeto donde el cliente únicamente está al principio. 

    p(data-aos="fade-down").mb-5 A continuación, se revisan los modelos del paradigma tradicional más utilizados.   

    .row.justify-content-center.align-items-start.mb-5
      .col-lg-10
        AcordionA(tipo="a" clase-tarjeta="tarjeta bg6")
          .row.justify-content-center.align-items-center(titulo="Modelo en cascada")
            p Uno de los primeros modelos de ciclo de vida del desarrollo fue establecido por W. Royce en 1970 y es conocido como el “modelo de cascada” (<i>waterfall model</i>). 

            p En su concepción básica, cada una de las actividades genera, como salidas, productos y modelos que son utilizados como entradas para el proceso subsiguiente; esto supone que una actividad debe terminarse (por lo menos, en algún grado) para empezar la siguiente.

            img.img-a.img-t.mb-2(src='@/assets/curso/temas/55.svg', alt='')
            figcaption.ps-4 Figura 1. Pasos en la algoritmia básica.


          .row.justify-content-center.align-items-center(titulo="Modelo espiral")
            p Fue diseñado por Boehm en el año 1988 y se basa en una serie de ciclos repetitivos para ir ganando madurez en el producto final. El espiral se repite las veces que sea necesario hasta que el cliente o el usuario obtenga la satisfacción de sus necesidades.

            p En este modelo hay 4 actividades que envuelven a las etapas: planificación, análisis de riesgo, implementación y evaluación. Una de sus principales ventajas es que los riesgos van disminuyendo conforme avanzan los ciclos o interacciones
            img.img-a.img-t.mb-2(src='@/assets/curso/temas/56.svg', alt='')
            figcaption.ps-4 Figura 2. Modelo espiral del ciclo de vida del desarrollo.


          .row.justify-content-center.align-items-center(titulo="Modelo interactivo o por prototipos")
            p Este modelo consiste en un procedimiento que permite al equipo de desarrollo diseñar y analizar una aplicación que represente el sistema que será implementado (McCracken y Jackson, 1982).
            .h6.my-3 Objetivos
            p Son un medio eficaz para aclarar los requisitos de los usuarios e identificar las características de un sistema que deben cambiarse o añadirse.  Mediante el prototipo se puede verificar la viabilidad del diseño de un sistema.
            .row
              .col-lg-5.border-y.offset-1.mt-3
                .col-sm.my-2
                  ol.lista-ol--cuadro
                    li 
                      .lista-ol--cuadro__vineta.colorv1(style="width: 60px;")
                        span A
                      | Son un medio eficaz para aclarar los requisitos de los usuarios e identificar las características de un sistema que deben cambiarse o añadirse. 
              .col-lg-5.border-y.offset-1.mt-3
                .col-sm.my-2
                  ol.lista-ol--cuadro
                    li 
                      .lista-ol--cuadro__vineta.colorv1(style="width: 40px;")
                        span B
                      | Mediante el prototipo se puede verificar la viabilidad del diseño de un sistema. 
            .row.mt-4
              .col-4
                img.img-a.img-t.mb-2(src='@/assets/curso/temas/58.png', alt='')

              .col-8
                p Las etapas del modelo son:
                .col.mt-3
                  .col-sm.my-2
                    ol.lista-ol--cuadro
                      li 
                        .lista-ol--cuadro__vineta.wtg-1
                          span.vtext 1
                        p.mb-0 Colecta y refinamiento de los requerimientos y proyecto rápido.
                      li.px-5
                        i.fas.fa-check.colorv
                        p.mb-0 Análisis.
                      li.px-5
                        i.fas.fa-check.colorv
                        p.mb-0 Especificación del prototipo.
                      li.mt-4 
                        .lista-ol--cuadro__vineta(style="width: 25px;")
                          span.vtext 2
                        p.mb-0 Diseño rápido.
                      li.mt-4 
                        .lista-ol--cuadro__vineta(style="width: 25px;")
                          span.vtext 3
                        p.mb-0 Construcción del prototipo.
                      li.mt-4 
                        .lista-ol--cuadro__vineta.wtg-4
                          span.vtext 4
                        p.mb-0 Evaluación del prototipo por el cliente.
                      li.mt-4 
                        .lista-ol--cuadro__vineta(style="width: 25px;")
                          span.vtext 5
                        p.mb-0 Refinamiento del prototipo.
                      li.px-5
                        i.fas.fa-check.colorv
                        p.mb-0 Diseño técnico.
                      li.px-5
                        i.fas.fa-check.colorv
                        p.mb-0 Programación y test.
                      li.px-5
                        i.fas.fa-check.colorv
                        p.mb-0 Operación y mantenimiento.
                      li.mt-4 
                        .lista-ol--cuadro__vineta(style="width: 25px;")
                          span.vtext 6
                        p.mb-0 Producto de ingeniería.
            img.img-a.img-t.mb-2(src='@/assets/curso/temas/57.svg', alt='')
            figcaption.ps-4 Figura 3. Modelo de iterativo o por prototipos. 


    p(data-aos="fade-down").mb-5 Con respecto a los modelos del ciclo de vida del paradigma ágil, estos se caracterizan por estar basados en etapas del ciclo de vida del <i>software</i> tradicional, pero combinándolas con algunas técnicas, al respecto se pueden revisar los siguientes: 

    .row.justify-content-center.align-items-start.mb-5
      .col-lg-10
        AcordionA(tipo="a" clase-tarjeta="tarjeta bg6")
          .row.justify-content-center.align-items-center(titulo="Modelo Scrum.")
            p Este modelo se basa en el desarrollo incremental, es decir conforme pasen las fases y la iteración mayor será el tamaño del proyecto que se está desarrollando.

            p Los procesos que utiliza son: 
            .row.mb-4
              .col-lg-6
                ol.lista-ol--cuadro
                  li 
                    .lista-ol--cuadro__vineta.wtg-1
                      span.vtext 1
                    p.mb-0 Product Backlog.
                  li 
                    .lista-ol--cuadro__vineta.wtg-1
                      span.vtext 2
                    p.mb-0 Sprint Backlog.
                  li 
                    .lista-ol--cuadro__vineta.wtg-1
                      span.vtext 3
                    p.mb-0 Sprint Planning Meeting.    
              .col-lg-6
                ol.lista-ol--cuadro
                  li 
                    .lista-ol--cuadro__vineta.wtg-1
                      span.vtext 4
                    p.mb-0 Daily Scrum.
                  li 
                    .lista-ol--cuadro__vineta.wtg-1
                      span.vtext 5
                    p.mb-0 Sprint Review.
                  li 
                    .lista-ol--cuadro__vineta.wtg-1
                      span.vtext 6
                    p.mb-0 Sprint Retrospective  
            p El Scrum consiste en realizar un análisis de los requerimientos del sistema (Product Backlog), señalar cuáles serán los objetivos a corto o mediano plazo dentro de un sprint, o sea, la fase de desarrollo. Posteriormente, los desarrolladores harán lo suyo, se realizarán algunas pruebas y se retroalimentará de acuerdo con lo conseguido al terminar la última fase. 
            h4 Ventajas

            ul.lista-ul
              li 
                i.fas.fa-check.colorv2
                p.mb-0 <b>Gestión regular de las expectativas del usuario:</b> los usuarios participan y proponen soluciones
              li 
                i.fas.fa-check.colorv2
                p.mb-0 <b>Resultados anticipados:</b> no es necesario esperar hasta el final para ver resultados
              li 
                i.fas.fa-check.colorv2
                p.mb-0 <b>Flexibilidad y adaptación:</b> se adapta a cualquier contexto, área o sector.
              li 
                i.fas.fa-check.colorv2
                p.mb-0 <b>Gestión sistemática de riesgos:</b> los problemas son gestionados en el mismo momento de su aparición. 

            img.img-a.img-t.mb-2(src='@/assets/curso/temas/59.svg', alt='')
            figcaption.ps-4 Figura 4. Modelo ágil Scrum.             
          .row.justify-content-center.align-items-center(titulo="Modelo Kanban.")
            p David J. Anderson (reconocido como el líder de pensamiento de la adopción del Lean/Kanban para el trabajo de conocimiento), formuló el método Kanban como una aproximación al proceso evolutivo e incremental y al cambio de sistemas para las organizaciones de trabajo. El método está enfocado en llevar a cabo las tareas pendientes y los principios más importantes pueden ser divididos en cuatro principios básicos y seis prácticas.

            p El modelo Kanban es uno de los modelos más visuales de las metodologías ágiles; este consiste en la creación de un tablero con etiquetas, donde se seccionan cada una de las fases de su desarrollo, además se clasifican de acuerdo con los equipos de trabajo y se les asignan objetivos a corto, mediano y largo plazo.

            p Mediante la metodología japonesa Kanban se:

            .row.mb-4
              .col-lg-6
                ol.lista-ol--cuadro
                  li 
                    .lista-ol--cuadro__vineta.wtg-1
                      span.vtext 1
                    p.mb-0 Define el flujo de trabajo.
                  li 
                    .lista-ol--cuadro__vineta.wtg-1
                      span.vtext 2
                    p.mb-0 Establecen las fases del ciclo de producción.
   
              .col-lg-6
                ol.lista-ol--cuadro
                  li 
                    .lista-ol--cuadro__vineta.wtg-1
                      span.vtext 3
                    p.mb-0 Stop Starting, start finishing. 
                  li 
                    .lista-ol--cuadro__vineta.wtg-1
                      span.vtext 4
                    p.mb-0 Tiene un control. 
            img.img-a.img-t.mb-2(src='@/assets/curso/temas/60.svg', alt='')
            figcaption.ps-4 Figura 5. Modelo ágil Kanban                    
          .row.justify-content-center.align-items-center(titulo="Modelo XP o programación extrema.")
            p La programación extrema o eXtreme Programming (XP) es un enfoque de la ingeniería de <i>software</i> formulado por Kent Beck, autor del primer libro sobre este tema: Extreme Programming Explained: Embrace Change (1999). Esta metodología es adaptable según las necesidades y requerimientos a implementar, además, el cliente se encuentra involucrado en el proceso de desarrollo lo que hace que el producto pueda ser terminado en un menor tiempo.
            .row.mb-4
              .col-lg-6
                ol.lista-ol--cuadro
                  li 
                    .lista-ol--cuadro__vineta.wtg-1
                      span.vtext 1
                    p.mb-0 Tipo de desarrollo iterativo e incremental.
                  li 
                    .lista-ol--cuadro__vineta.wtg-1
                      span.vtext 2
                    p.mb-0 Pruebas unitarias.
                  li 
                    .lista-ol--cuadro__vineta.wtg-1
                      span.vtext 3
                    p.mb-0 Trabajo en Equipo.
                  li 
                    .lista-ol--cuadro__vineta.wtg-1
                      span.vtext 4
                    p.mb-0 Trabajo junto al cliente.
   
              .col-lg-6
                ol.lista-ol--cuadro
                  li 
                    .lista-ol--cuadro__vineta.wtg-1
                      span.vtext 5
                    p.mb-0 Corrección de errores.
                  li 
                    .lista-ol--cuadro__vineta.wtg-1
                      span.vtext 6
                    p.mb-0 Reestructuración del código.
                  li 
                    .lista-ol--cuadro__vineta.wtg-1
                      span.vtext 7
                    p.mb-0 El código es de todos.
                  li 
                    .lista-ol--cuadro__vineta.wtg-1
                      span.vtext 8
                    p.mb-0 El código simple es la clave. 
            p Características principales de la programación extrema: 
            img.img-a.img-t.mb-2(src='@/assets/curso/temas/61.svg', alt='')
            figcaption.ps-4 Figura 6. Modelo XP                                    
</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    datosSlyder: [
      {
        titulo: 'FASE PLANIFICACIÓN:',
        texto:
          'En esta primera fase se realiza el planteamiento del problema, se definen alcances y objetivos del <i>software</i>.<br><br><b>Objetivos:</b> estudio de viabilidad, realizar planificación detallada.',
        imagen: require('@/assets/curso/temas/44.png'),
      },
      {
        titulo: 'FASE ANÁLISIS (definición de requisitos):',
        texto:
          'Esta fase busca definir los requisitos que son los que dirigirán el desarrollo del proyecto de <i>software</i>.<br><br><b>Objetivos:</b> conocer los requisitos, asegurar que los requisitos son alcanzables, formalizar acuerdo con el cliente.',
        imagen: require('@/assets/curso/temas/45.png'),
      },
      {
        titulo: 'FASE DISEÑO:',
        texto:
          'En esta fase se estudian posibles opciones de implementación para el <i>software</i> que hay que construir, estructura general del mismo.<br><br><b>Objetivos:</b> identificar soluciones tecnológicas, asignar recursos materiales, proponer identificar y seleccionar, establecer métodos de validación, ajustar especificaciones.',
        imagen: require('@/assets/curso/temas/46.png'),
      },
      {
        titulo: 'FASE PRUEBAS:',
        texto:
          'Esta fase busca detectar fallos cometidos en las etapas anteriores para corregirlos.<br><br><b>Objetivos:</b> realizar los ajustes necesarios para corregir posibles errores o inconsistencias.',
        imagen: require('@/assets/curso/temas/47.png'),
      },
      {
        titulo: 'FASE MANTENIMIENTO:',
        texto:
          'En esta fase se realizan tres puntos referenciados: mantenimiento correctivo, mantenimiento adaptativo y mantenimiento perfectivo.<br><br><b>Objetivos:</b> operación asegurar que el uso del proyecto es el que se pretendía, mantenimiento.',
        imagen: require('@/assets/curso/temas/48.png'),
      },
    ],
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
