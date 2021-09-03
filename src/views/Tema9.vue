<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 9
      h1 Desarrollo de modelos de blusa niña

    p.mb-5(data-aos="flip-up") Se llama desarrollo de modelos a la creación de los patrones específicos de un modelo, es decir los moldes para poder confeccionar el diseño solicitado. A continuación, se presentan algunos diseños o desarrollos:

    .tarjeta.tarjeta--gris.p-4.mb-5(data-aos="flip-up")
  
      PasosB.color-acento-contenido

        .row.justify-content-center(titulo="")
          .col-lg-10
            .titulo-sexto.color-acento-contenido
              h5 Figura 119
              p.mb-0 #[i Blusa tipo marinero]
            figure
              img.mb-3(src='@/assets/curso/tema_9/img_1.png', alt='Texto que describa la imagen')
              figcaption Nota. Manual de Patronaje Básico e interpretación de diseños (Gutiérrez Rengifo et al., 2011)


        .row.justify-content-center(titulo="")
          .col-lg-10
            .titulo-sexto.color-acento-contenido
              h5 Figura 120
              p.mb-0 #[i Blusa cuello bebé manga bombacha]
            figure
              img.mb-3(src='@/assets/curso/tema_9/img_2.png', alt='Texto que describa la imagen')
              figcaption Nota. Manual de Patronaje Básico e interpretación de diseños (Gutiérrez Rengifo et al., 2011)

        .row.justify-content-center(titulo="")
          .col-lg-10
            .titulo-sexto.color-acento-contenido
              h5 Figura 121
              p.mb-0 #[i Camisera]
            figure
              img.mb-3(src='@/assets/curso/tema_9/img_3.png', alt='Texto que describa la imagen')
              figcaption Nota. Manual de Patronaje Básico e interpretación de diseños (Gutiérrez Rengifo et al., 2011)

        .row.justify-content-center(titulo="")
          .col-lg-10
            .titulo-sexto.color-acento-contenido
              h5 Figura 122
              p.mb-0 #[i Blusa Ranglan]
            figure
              img.mb-3(src='@/assets/curso/tema_9/img_4.png', alt='Texto que describa la imagen')
              figcaption Nota. Manual de Patronaje Básico e interpretación de diseños (Gutiérrez Rengifo et al., 2011)

        .row.justify-content-center(titulo="")
          .col-lg-10
            .titulo-sexto.color-acento-contenido
              h5 Figura 123
              p.mb-0 #[i Jardinera]
            figure
              img.mb-3(src='@/assets/curso/tema_9/img_5.png', alt='Texto que describa la imagen')
              figcaption Nota. Manual de Patronaje Básico e interpretación de diseños (Gutiérrez Rengifo et al., 2011)

    p.text-center Es muy importante explorar más modelos y practicar desarrollos para adquirir la habilidad y experiencia necesaria para la construcción de patrones.    



    

</template>

<script>
export default {
  name: 'Tema9',
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

<style lang="sass" scoped></style>
