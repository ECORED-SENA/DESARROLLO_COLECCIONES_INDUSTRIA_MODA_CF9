<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 12
      h1 Básico del vestido

    p.mb-5(data-aos="flip-up") El vestido es una prenda de vestir enteriza generalmente femenina, que en su parte inferior está compuesta por la falda. Para desarrolla se parte de la base de blusa infantil, haciendo las siguientes modificaciones: prolongar los CF y CA, desde el punto de costado por cintura bajar la medida de largo falda y escuadrar uniendo el costado con el centro de cada patrón, ver figura:

    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-lg-6
        .titulo-sexto.color-acento-contenido
          h5 Figura 142
          p.mb-0 #[i Pasos básicos para vestido infantil]
        figure
          img.img-a(src='@/assets/curso/tema_12/img_1.png', alt='Texto que describa la imagen')
          figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator

    p.text-center.mb-5(data-aos="flip-up") Suavizar curva de cadera, quedando así el delantero y el posterior del básico de vestido infantil, Ver figura:

    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-lg-6
        .titulo-sexto.color-acento-contenido
          h5 Figura 143
          p.mb-0 #[i Básico de vestido infantil]
        figure
          img.img-a(src='@/assets/curso/tema_12/img_2.png', alt='Texto que describa la imagen')
          figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator

    .row.justify-content-center.mb-5
      .col-lg-8
        .cajon.color-secundario.p-4.mb-5(data-aos="flip-up")
          .row.align-items-center
            .col-lg-2
              figure
                img.img-a(src='@/assets/curso/tema_3/img_28.png', alt='Texto que describa la imagen')
            .col-lg-10
              p.mb-0 #[strong Nota:] al igual que con las anteriores bases se realizan las modificaciones necesarias para la creación de los modelos o diseños.

    h4 Escalado del vestido

    p.mb-5 Como el vestido es una pieza enteriza que une la parte superior con la inferior, se deben trasladar los incrementos verticales de la cintura de ambas prendas, así: la cantidad de escalado de la cintura del corpiño de transfiere y suma a los puntos de sisa por costado, vértice de pinza, sisa por hombro, escote por hombro y escote por centro. Los puntos de escalado de la cintura de la falda se trasladan y suman a los puntos cadera por costado, vértice de pinza, costado por bajo y bajo por centro. Ver imagen.

    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-lg-6
        .titulo-sexto.color-acento-contenido
          h5 Figura 144
          p.mb-0 #[i Explicación de escalado vestido]
        figure
          img.img-a(src='@/assets/curso/tema_12/img_3.png', alt='Texto que describa la imagen')
          figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator

    h4.text-center.mb-5 Al sumar dichos puntos quedaría así:

    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-lg-6
        .titulo-sexto.color-acento-contenido
          h5 Figura 145
          p.mb-0 #[i Sumas de escalado del vestido infantil]
        figure
          img.img-a(src='@/assets/curso/tema_12/img_5.png', alt='Texto que describa la imagen')
          figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator

    h4.text-center.mb-5 Quedando así el esquema del escalado del vestido infantil:

    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-lg-6
        .titulo-sexto.color-acento-contenido
          h5 Figura 146
          p.mb-0 #[i Esquema de escalado del Vestido infantil]
        figure
          img.img-a(src='@/assets/curso/tema_12/img_6.png', alt='Texto que describa la imagen')
          figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator
   


</template>

<script>
export default {
  name: 'Tema12',
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
