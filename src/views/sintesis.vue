<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-sexto.colo-acento-contenido.mb-4(data-aos="zoom-in-left")
      h5 Desarrollo e Implementación de Soluciones para la Transformación Digital
        span
          | Migración de servicios en la nube.
    figure.mt-4.mb-5(data-aos="zoom-in-left")

    .tarjeta.color-acento-contenido-2.mb-4.py-2
      .row.justify-content-center.align-items-center
        .col-auto.my-3.mx-4
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/introduccion/img1.png', alt='')
        .col-8.my-3
          .bg-white-r.mb-3.p-2.mt-4.mx-6.my-6.fw-bold 
            p.mb-0 Los servicios en la  nube son infraestructuras, plataformas o sistemas de software que alojan los proveedores externos y que se ponen a disposición de los usuarios a través de Internet. Facilitan el flujo de datos de los usuarios a través de Internet, referenciando lo anterior la migración de los diferentes servicios requiere de diferentes formas de almacenamiento, metodologías o estrategias de migración y monitorización. 
          p.mb-0 A continuación, se presenta el diagrama que representa el resumen de las temáticas que están desarrolladas en el componente formativo: 
    
    .row.justify-content-center
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/temas/sintesis.png", alt="alt")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis
    
</template>

<script>
export default {
  name: 'Sintesis',
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
