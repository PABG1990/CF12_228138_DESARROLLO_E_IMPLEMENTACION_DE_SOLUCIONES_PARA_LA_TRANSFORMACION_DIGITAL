<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-botones
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .tarjeta.color-acento-contenido-2.mb-4.py-2
      .row.justify-content-center.align-items-center
        .col-auto.my-3.mx-4
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/introduccion/img1.png', alt='')
        .col-8.my-3
          .bg-white-r.mb-3.p-2.mt-4.mx-6.fw-bold 
            p.mb-0 La claridad conceptual en relación a la computación en la nube se debe abordar de una manera holística para el entendimiento de los servicios bajo este concepto y se adquieren conocimientos acerca de arquitecturas, modelos, opciones, servicios de almacenamiento, y #[em software] de virtualización, para la migración a sistemas tecnológicos y optimizar procesos y recursos con mejor proyección.
          p(data-aos="fade-down") En el siguiente vídeo se  describe #[b la importancia de la implementación de soluciones para la transformación digital en las empresas, así:]
    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-12(data-aos="fade-left")
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="Description" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
          figcaption Video. Description
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
