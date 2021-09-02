<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 6
      h1 Desarrollo de modelo de overol

    p.mb-5 El overol es una prenda enteriza que se utiliza mucho en las líneas infantiles, viene del anglicismo Over All, que significa sobre todo. Para la realización de este patrón se requieren la base superior infantil y la base pantalón infantil, ambas en la misma talla. Veamos el paso a paso para la construcción de este modelo:

    .list.mb-5
      .list__item
          .list__item__bulletNumber 
            span 1
      .list__txt    
        p Se inicia marcando el pantalón (delantero y posterior), se traza una línea guía continuando el tiro. Sobre esa línea guía se hace coincidir el centro de la parte superior, frente con delantero, espalda con posterior, dejando una distancia de mínimo 4 cm en el costado para desahogos (esta distancia puede variar según necesidad o diseño).

    .row.justify-content-center.mb-5
      .col-lg-6
        .titulo-sexto.color-acento-contenido
          h5 Figura 102
          p.mb-0 #[i Pasos Overol.]
        figure
          img.img-a(src='@/assets/curso/tema_6/img_1.png', alt='Texto que describa la imagen')
          figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator

    .hr_bg01.mb-5

    .list.mb-5
      .list__item
          .list__item__bulletNumber 
            span 2
      .list__txt    
        p Unir por centro y costados, siempre utilizando el patrón más amplio, quedando así la base de overol sobre la que se pueden desarrollar diferentes diseños.

    .row.justify-content-center.mb-5
      .col-lg-6
        .titulo-sexto.color-acento-contenido
          h5 Figura 103
          p.mb-0 #[i Base Overol.]
        figure
          img.img-a(src='@/assets/curso/tema_6/img_2.png', alt='Texto que describa la imagen')
          figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator

    .hr_bg01.mb-5

    .list.mb-5
      .list__item
          .list__item__bulletNumber 
            span 3
      .list__txt    
        p Una variación muy común del overol es el carpintero, se traza según diseño sobre la base del overol, así:

    .row.justify-content-center
      .col-lg-6
        .titulo-sexto.color-acento-contenido
          h5 Figura 104
          p.mb-0 #[i Carpintero]
        figure
          img.img-a(src='@/assets/curso/tema_6/img_3.png', alt='Texto que describa la imagen')
          figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator

</template>

<script>
export default {
  name: 'Tema6',
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
