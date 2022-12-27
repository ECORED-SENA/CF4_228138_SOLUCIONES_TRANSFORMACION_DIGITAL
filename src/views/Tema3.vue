<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Fase de definición de requisitos
    .row.justify-content-center.align-items-start.mb-4
      .col-lg-6.my-3
        p(data-aos="fade-down") En esta primera fase del ciclo de vida del <i>software</i>, también llamada fase de análisis, se recopila, se examina y se formulan los requisitos del cliente, así como la verificación de las posibles restricciones que se puedan aplicar.

        p(data-aos="fade-down") Por eso, la etapa de análisis en el ciclo de vida del <i>software</i> corresponde al proceso a través del cual se intenta descubrir qué es lo que realmente se necesita y se llega a una comprensión adecuada de los requerimientos del sistema (las características que el sistema debe poseer).      
      .col-lg-6.my-3
        img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/62.png', alt='')
    .bg3.p-5
      .cajon-b.color-acento-contenido.mb-4.py-2
        .row.align-items-center.justify-content-center
          .col-auto.my-3
            img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/63.png', alt='')  
          .col-10.my-3
            p(data-aos="fade-down") La etapa de análisis es esencial debido a que sin esta no se sabe con precisión qué es lo que se necesita y ningún proceso de desarrollo permitirá obtenerlo. El problema que se presenta es que al inicio del desarrollo el cliente no sepa exactamente lo que necesita; por tanto, se debe averiguar con ayuda de distintas técnicas.
         
      p(data-aos="fade-down") De otra parte, la inestabilidad de los requerimientos de un sistema es inevitable, pues se estima que 25% de los requerimientos iniciales de un sistema cambian antes de que el sistema comience a utilizarse. Por ello, muchas prácticas resultan efectivas para gestionar adecuadamente los requerimientos de un sistema y, en cierto modo, controlar su evolución.

      p(data-aos="fade-down").mb-5 En la siguiente tabla, se describen las actividades y los artefactos que se realizan en la fase de definición de requisitos.  

      h4(data-aos="fade-down").mb-5 En la siguiente tabla, se describen las actividades y los artefactos que se realizan en la fase de definición de requisitos.
      .tabla-a
        table
          caption Tabla 1/ Actividades y artefactos de la fase de definición de requisitos
          thead
            tr
              th Fase
              th Actividades
              th Artefactos
          tbody
            tr
              td(rowspan='6') Análisis (definición de requisitos).
            tr
              td Definición del alcance del proyecto.
              td 
            tr
              td Identificación del negocio.
              td Modelo del negocio.
            tr
              td Toma de requerimientos.
              td Análisis y realización de casos de uso.
            tr
              td Estudio de procesos de negocio.
              td Modelo de procesos y actividades de negocio.
            tr
              td Calendarización del proyecto.
              td Cronograma del proyecto.             
</template>

<script>
export default {
  name: 'Tema3',
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
