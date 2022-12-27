<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Ingeniería de requisitos
    .row.justify-content-center.align-items-start.mb-5
      .col-lg-10
        img.img-a.img-t.mb-5(data-aos="zoom-in")(src='@/assets/curso/temas/74.png', alt='')
        p(data-aos="fade-down").text-center Las siguientes son definiciones de ingeniería de requisitos de algunos autores.

    SlyderF.mb-5(columnas="col-lg-12")
      .tarjeta
        .bloque-texto-c.color-secundario.p-4
          i.fas.fa-quote-right
          h4.mb-2 La ingeniería de requisitos es la disciplina para desarrollar una especificación completa, consistente y no ambigua, la cual servirá como base para acuerdos comunes entre todas las partes involucradas y en dónde se describen las funciones que realizará el sistema.
          span - (Boehm, 1979).  
      .tarjeta
        .bloque-texto-c.color-secundario.p-4
          i.fas.fa-quote-right
          h4.mb-2 La ingeniería de requisitos es el proceso de estudiar las necesidades del usuario para llegar a una definición de requisitos de sistema, hardware o <i>software</i>.
          span - (IEEE, 1990).    
      .tarjeta
        .bloque-texto-c.color-secundario.p-4
          i.fas.fa-quote-right
          h4.mb-2 La ingeniería de requisitos puede considerarse como un proceso de descubrimiento y comunicación de las necesidades de clientes y usuarios y la gestión de los cambios de dichas necesidades.
          span - (Amador, 2000)

    p(data-aos="fade-down").mb-5 El término IR <b>“ingeniería de requisitos”</b> ha surgido para englobar los procesos de desarrollo y gestión de requisitos en el ciclo de vida del <i>software</i>, el primer término (ingeniería) se enfoca en las actividades de obtención, análisis, especificación y validación de los requisitos que permitirá alcanzar los objetivos del negocio y el segundo (requisitos) está centrado en la administración de los mismos y tiene como propósito central la gestión de los cambios y la trazabilidad, de esta forma la IR proporciona el mecanismo apropiado para: 

    .row.justify-content-center.align-items-start.mb-4
      .col-lg-3.my-3
        img.img-a.img-t.mb-5(data-aos="zoom-in")(src='@/assets/curso/temas/75.png', alt='') 
      .col-lg-9.my-3
        ul.lista-ul
          li 
            i.fas.fa-angle-right.vcolor
            p.mb-0 Entender lo que el cliente quiere.
          li 
            i.fas.fa-angle-right.vcolor
            p.mb-0 Analizar las necesidades.
          li 
            i.fas.fa-angle-right.vcolor
            p.mb-0 Evaluar la factibilidad.
          li 
            i.fas.fa-angle-right.vcolor
            p.mb-0 Negociar una solución razonable.
          li 
            i.fas.fa-angle-right.vcolor
            p.mb-0 Especificar la solución sin ambigüedades.
          li 
            i.fas.fa-angle-right.vcolor
            p.mb-0 Validar la especificación.
          li 
            i.fas.fa-angle-right.vcolor
            p.mb-0 Administrar los requisitos conforme éstos se transforman en un sistema operacional.   

    h4(data-aos="fade-down") Etapas de la ingeniería de requisitos 
    p(data-aos="fade-down").mb-5 Hay cuatro (4) etapas en un proceso usual de ingeniería de requisitos y que son utilizadas para el desarrollo de un producto único, a saber: elicitación, análisis, especificación y validación de los requisitos. 

    .row.justify-content-center.align-items-start
      .col-lg-10
        AcordionA(tipo="a" clase-tarjeta="tarjeta bg6")
          .row.justify-content-center.align-items-center(titulo="Elicitación") 
            p Actividad involucrada en el descubrimiento de los requisitos del sistema. Aquí los analistas deben trabajar junto con el cliente para descubrir el problema que el sistema debe resolver, los diferentes servicios que el sistema debe prestar y las restricciones que se pueden presentar.

            p Los principales objetivos que se deben alcanzar son los siguientes:
            .row.justify-content-center.align-items-center.bgw             
              .col-lg-4.col-md-12
                img.img-a.img-t(src='@/assets/curso/temas/76.png', alt='')                   
              .col-lg-8.col-md-12
                .p-3
                  ul.lista-ul.mb-0
                    li 
                      i.fas.fa-angle-right.vcolor
                      p.mb-0 Conocer el dominio del problema, de forma tal que los analistas puedan entenderse con los clientes y usuarios y sean capaces de transmitir dicho conocimiento al resto del equipo.

                    li 
                      i.fas.fa-angle-right.vcolor
                      p.mb-0 Descubrir necesidades reales entre clientes y usuarios, haciendo énfasis en aquellas que la mayor parte de las veces se asumen y toman por implícitas.

                    li 
                      i.fas.fa-angle-right.vcolor
                      p.mb-0 Consensuar los requisitos entre los propios clientes y usuarios hasta obtener una visión común de los mismos.    

          .row.justify-content-center.align-items-center(titulo="Análisis") 
            p Sobre la base de la obtención realizada previamente, comienza esta fase la cual tiene como propósito descubrir problemas con los requisitos del sistema identificados hasta el momento, para ello se basa en los siguientes objetivos:
            .row.justify-content-center.align-items-center.bgw             
              .col-lg-4.col-md-12
                img.img-a.img-t(src='@/assets/curso/temas/77.png', alt='')                   
              .col-lg-8.col-md-12
                .p-3
                  ul.lista-ul.mb-0
                    li 
                      i.fas.fa-angle-right.vcolor
                      p.mb-0 Detectar conflicto en los requisitos que suelen provenir de distintas fuentes y presentar contradicciones o ambigüedades debido a su naturaleza informal.
                    li 
                      i.fas.fa-angle-right.vcolor
                      p.mb-0 Profundizar en el conocimiento del dominio del problema puede facilitar el proceso de construir un producto útil para clientes y usuarios (Durán, 2000).    
            p.mt-4 En esta fase, el analista proporciona un sistema de retroalimentación que refina el entendimiento conseguido en la etapa de obtención.
          .row.justify-content-center.align-items-center(titulo="Especificación") 
            .col-lg-4.col-md-12
              img.img-a.img-t(src='@/assets/curso/temas/78.png', alt='')                   
            .col-lg-8.col-md-12
              p Aquí se documentan los requisitos acordados con el cliente, en un nivel apropiado de detalle. En la práctica, esta etapa se realiza conjuntamente con el análisis, por lo que se puede decir que la especificación es el “pasar en limpio” el análisis realizado previamente aplicando técnicas y/o estándares de documentación, como la notación UML (Lenguaje de Modelado Unificado), que es un estándar para el modelado orientado a objetos, por lo que los casos de uso y la obtención de requisitos basada en los casos de uso se utilizan cada vez más para la obtención de requisitos.    

          .row.justify-content-center.align-items-center(titulo="Validación") 
            .col-lg-4.col-md-12
              img.img-a.img-t(src='@/assets/curso/temas/79.png', alt='')                   
            .col-lg-8.col-md-12
              p Por último, la validación garantiza que los requisitos, una vez analizados y resueltos los posibles conflictos, correspondan realmente a las necesidades de clientes y usuarios, para evitar que, a pesar de que el producto final sea técnicamente correcto, no sea satisfactorio. La validación puede llevar al analista a reescribir algunas especificaciones de requisitos y, en otros casos, a obtener nuevos, producto de la aparición de necesidades que hasta entonces estaban ocultas, para volver a evaluar el análisis inicial, o para corregir y perfeccionar el conjunto de requisitos documentados.         
</template>

<script>
export default {
  name: 'Tema5',
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
