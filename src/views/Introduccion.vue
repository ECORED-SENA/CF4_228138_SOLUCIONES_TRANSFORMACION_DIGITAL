<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .cajon-b.color-acento-contenido.mb-4.py-2
      .row.align-items-center.justify-content-center
        .col-auto.my-3
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/1.png', alt='')  
        .col-10.my-3
          p(data-aos="fade-down") En este componente se abordarán los conceptos y los fundamentos para realizar la documentación e informe de requisitos con base en las buenas prácticas, además se abordarán los conceptos acerca del ciclo de vida del <i>software</i> y las aplicaciones web. Vea un video que contextualiza al respecto: 

    .row.justify-content-center.align-items-center.mb-5           
      .col-lg-12(data-aos="fade-left")     
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/avq_BGDthIU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)               
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
