<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 10
      h1 Escalado de la blusa niña

    p.mb-5(data-aos="flip-up") El escalado de la blusa infantil es muy similar al de la camisa infantil, sólo varía en el desplazamiento de las pinzas, ver figura:

    .row.justify-content-center(data-aos="flip-up")
      .col-lg-10
        .titulo-sexto.color-acento-contenido
          h5 Figura 124
          p.mb-0 #[i Escalado de blusa infantil]
        figure
          img.mb-3(src='@/assets/curso/tema_9/img_6.png', alt='Texto que describa la imagen')
          figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

    

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

<style lang="sass" scoped></style>
