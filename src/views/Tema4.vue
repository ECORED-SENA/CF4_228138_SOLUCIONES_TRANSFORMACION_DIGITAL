<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Requisitos

    .row.justify-content-center.align-items-start.mb-4
      .col-lg-6.my-3
        .bloque-texto-c.color-secundario.p-4
          i.fas.fa-quote-right
          h2.mb-2 Un requisito es una condición o capacidad que necesita el usuario para resolver un problema o conseguir un objetivo determinado (IEEE, 1990).     
      .col-lg-4.my-3
        img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/64.png', alt='') 

      .col-lg-10 
        p(data-aos="fade-down").mb-0 Los requisitos comunican las expectativas de los consumidores de productos <i>software</i>; de otra parte, los requisitos pueden ser obvios o estar ocultos, conocidos o desconocidos, esperados o inesperados, desde el punto de vista del cliente.
    Separador 
    #t_4_1.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 4.1 Importancia de los requisitos

    p(data-aos="fade-down").mb-5 Los requisitos cobran importancia dentro del ciclo de vida del <i>software</i>, puesto que:
    .row.mb-5
      .col-12.col-md-8
        .row.mt-2(data-aos="fade-right")
          .col-12
            .row
              .col-1.col-lg-1.offset-1.align-self-center.justify-content-center
                img(src='@/assets/curso/temas/66.png', alt='', style='margin-right: -100px').w-100
              .col-9.py-3.border-y
                .col-sm.mb-5.mb-sm-0.mt-2.mx-5
                  p.mt-3 Establecen el alcance del trabajo subsecuente, pueden definir estrategias de desarrollo, riesgos, tomar decisiones de negocio (viabilidad de negocio), de proyecto (tiempo, recursos), de sistema (arquitectura).
        .row.mt-0(data-aos="fade-left")
          .col-12
            .row
              .col-1.col-lg-1.offset-1.align-self-center.justify-content-center
                img(src='@/assets/curso/temas/67.png', alt='', style='margin-right: -100px').w-100
              .col-9.py-3.border-bot
                .col-sm.mb-5.mb-sm-0.mt-2.mx-5
                  p.mt-3 Indican al equipo del proyecto qué requieren los usuarios (necesidades de negocio).
        .row.mt-0(data-aos="fade-right")
          .col-12
            .row
              .col-1.col-lg-1.offset-1.align-self-center.justify-content-center
                img(src='@/assets/curso/temas/68.png', alt='', style='margin-right: -100px').w-100
              .col-9.py-3.border-bot
                .col-sm.mb-5.mb-sm-0.mt-2.mx-5
                  p.mt-3 El éxito o fracaso de un proyecto está altamente influenciado por la calidad de los requisitos y el proceso para gestionarlos durante el desarrollo de un producto.
      .col-4.d-none.d-md-block
        figure(style="text-align: -webkit-center;")
          img(src='@/assets/curso/temas/65.png', alt='Texto que describa la imagen').w-100
    p(data-aos="fade-down").mb-5 En la siguiente figura se pueden revisar las características que los requisitos deben cumplir de acuerdo con Pfleeger (2002).  

    .row.justify-content-center.align-items-start.mb-4
      .col-lg-3.my-3
        img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/69.png', alt='')      
      .col-lg-9.my-3
        .tarjeta.tarjeta--gris.p-4.mb-5
          LineaTiempoC.color-acento-contenido
            .row.justify-content-center.align-items-start(titulo="Necesario")
              .col-11
                p Si se tiene alguna duda acerca de la necesidad del requerimiento, se puede preguntar <b>“¿Qué sería lo peor de no incluirlo?”</b> Si no se encuentra una respuesta o cualquier consecuencia, entonces es probable que no sea un requerimiento necesario. 
            .row.justify-content-center.align-items-start(titulo="Completo")
              .col-11
                p Un requerimiento está completo si no necesita ampliar detalles en su redacción, es decir, si se proporciona la información suficiente para su comprensión. 
            .row.justify-content-center.align-items-start(titulo="Consistente")
              .col-11
                p Un requerimiento es consistente si no es contradictorio con otro requerimiento. 
            .row.justify-content-center.align-items-start(titulo="Correcto")
              .col-11
                p Acuerdo entre dos partes. Contiene una sola idea 
            .row.justify-content-center.align-items-start(titulo="Factible")
              .col-11
                p El requerimiento deberá de ser totalmente factible y dentro de presupuesto, calendario y otras restricciones, si se tiene alguna duda de su factibilidad, hay que investigar, generar pruebas de concepto para saber su complejidad y factibilidad, si aun así el requerimiento es no factible, hay que revisar la visión del sistema y replantear el requerimiento. 
            .row.justify-content-center.align-items-start(titulo="Modificable")
              .col-11
                p Los cambios en los requisitos deben hacerse de manera sistemática, y debe tenerse en cuenta su impacto en otros requisitos. 
            .row.justify-content-center.align-items-start(titulo="Priorizado")
              .col-11
                p Ategorizar el requerimiento nos ayuda a saber el grado de necesidad del mismo: esencial/crítico, deseado, opcional verificable. 
            .row.justify-content-center.align-items-start(titulo="Verificable")
              .col-11
                p Si un requerimiento no se puede comprobar, entonces, ¿cómo se sabe si se cumplió con él o no? Debe ser posible verificarlo ya sea por inspección, análisis de prueba o demostración. Cuando se escriba un requerimiento, se deberán determinar los criterios de aceptación. 
            .row.justify-content-center.align-items-start(titulo="Rastreable")
              .col-11
                p La especificación se debe organizar de tal forma que cada función del sistema se pueda rastrear hasta su conjunto de requerimientos correspondiente. Facilita las pruebas y la validación del diseño. 
            .row.justify-content-center.align-items-start(titulo="Claro")
              .col-11
                p Un requerimiento es conciso si es fácil de leer y entender, su redacción debe ser simple y clara para quienes lo consulten en un futuro.

    Separador 
    #t_4_2.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 4.2 Clasificación

    p(data-aos="fade-down").mb-5 Los requerimientos se pueden definir de distintas maneras, la primera clasificación se encuentra relacionada con el nivel de descripción con la que cuentan estos y dentro de este tipo de clasificación se encuentran:

    .row.justify-content-center.align-items-start.mb-5
      .col-lg-10
        AcordionA(tipo="a" clase-tarjeta="tarjeta bg6")
          .row.justify-content-center.align-items-center(titulo="Requerimientos de usuario") 
            .col-lg-4.col-md-12.my-3
              img.img-a.img-t(src='@/assets/curso/temas/70.png', alt='')                   
            .col-lg-8.col-md-12.my-3
              p Son declaraciones, en lenguaje natural y en diagramas, de los servicios que se espera que el sistema proporcione y de las restricciones bajo las cuales debe funcionar. 

          .row.justify-content-center.align-items-center(titulo="Requerimientos de sistema") 
            .col-lg-4.col-md-12.my-3
              img.img-a.img-t(src='@/assets/curso/temas/71.png', alt='')                   
            .col-lg-8.col-md-12.my-3
              p Estos requerimientos establecen con detalle las funciones, servicios y restricciones operativas del sistema. El documento de requerimientos del sistema deberá ser preciso, y definir exactamente lo que se va a desarrollar.               

    p(data-aos="fade-down").mb-5 En la siguiente clasificación se observa la que se da a los requerimientos del sistema, la cual se encuentra dividida con base en lo que se va a describir, las clasificaciones son:

    .row.justify-content-center.align-items-start.mb-5
      .col-lg-10
        AcordionA(tipo="a" clase-tarjeta="tarjeta bg6")
          .row.justify-content-center.align-items-center(titulo="Requerimientos funcionales") 
            .col-lg-4.col-md-12.my-3
              img.img-a.img-t(src='@/assets/curso/temas/72.png', alt='')                   
            .col-lg-8.col-md-12.my-3
              p Son declaraciones de los servicios que debe proporcionar el sistema, de la manera en que este debe reaccionar a entradas particulares; o también pueden declarar explícitamente lo que el sistema no debe hacer. 

          .row.justify-content-center.align-items-center(titulo="Requerimientos no funcionales") 
            .col-lg-4.col-md-12.my-3
              img.img-a.img-t(src='@/assets/curso/temas/73.png', alt='')                   
            .col-lg-8.col-md-12.my-3
              p Son restricciones de los servicios o funciones ofrecidos por el sistema. Incluyen restricciones de tiempo, sobre el proceso de desarrollo y estándares. Dentro de estos requerimientos se encuentra todo lo referente a la fiabilidad, el tiempo de respuesta y la capacidad de almacenamiento. 
    .row.justify-content-center.align-items-start
      .col-lg-10                
        p(data-aos="fade-down").mb-5.text-center En la siguiente tabla se presentan algunos ejemplos sobre requisitos funcionales y no funcionales. 
        .tabla-a(data-aos="fade-left")
          table
            caption Tabla 2/ Requisitos.
            thead
              tr
                th Funcionales
                th No funcionales
            tbody.text-center
              tr
                td Se debe ingresar cédula, nombre y teléfono de cada cliente.
                td Las consultas deben resolverse en menos de 3 segundos.
              tr
                td Se requiere un listado de clientes por zona.
                td El lenguaje de programación debe ser Java.
              tr
                td(colspan='2') Se puede ampliar el tema de requisitos funcionales y no funcionales en los videos que se proponen dentro del material complementario.                          
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
