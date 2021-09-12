<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 8
      h1 Variaciones de la blusa: cuellos, almillas y mangas

    p.mb-5 A continuación, se presentan las diferentes variaciones de la blusa.

    h4.mb-5 Cuellos

    p.mb-0 Al igual que en las demás líneas, existen innumerables variaciones en cuanto a cuellos se refiere, a continuación se mostrarán algunos de ellos y cómo realizarlos.
    p.mb-5 Cuellos de solapa o de sobreponer: son el tipo de cuellos que van sobre la prenda, en infantil son muy utilizados, los más comunes son el cuello Peter Pan o cuello bebé y el marinero.

    figure.mb-5
      img.img-a(src='@/assets/curso/tema_8/img_1.png', alt='Texto que describa la imagen')

    p.mb-5 Para realizarlos se parte de la base de blusa o de la prenda superior a la cual se le realizará. Se unen el frente y la espalda por el punto de hombro con escote, se deja una separación de 1,5 cm entre los puntos de hombro por sisa y se traza el cuello a realizar, ver figura:

    .row.justify-content-center.mb-5
      .col-lg-5
        .titulo-sexto.color-acento-contenido
          h5 Figura 112
          p.mb-0 #[i Cuello]
        figure
          img.mb-3.img-a(src='@/assets/curso/tema_8/img_2.png', alt='Texto que describa la imagen')
          figcaption.d-flex Nota. Fuente: Shutterstock
      .col-lg-5
        .titulo-sexto.color-acento-contenido
          h5 Figura 113
          p.mb-0 #[i Cuello bebé o Peter Pan]
        figure
          img.mb-3.img-a(src='@/assets/curso/tema_8/img_3.png', alt='Texto que describa la imagen')
          figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

    p.mb-5 Si el cuello va sobre un escote diferente, éste debe modificarse antes de desarrollar el cuello, por ejemplo en el caso del cuello marinero, el escote del frente es en forma de V. Ver figura:

    .row.justify-content-center.mb-5
      .col-lg-5
        .titulo-sexto.color-acento-contenido
          h5 Figura 114
          p.mb-0 #[i Ejemplo cuello marinero]
        figure
          img.mb-3.img-a(src='@/assets/curso/tema_8/img_4.png', alt='Texto que describa la imagen')
          figcaption Nota. Fuente: Freepik
      .col-lg-5
        .titulo-sexto.color-acento-contenido
          h5 Figura 115
          p.mb-0 #[i Cuello marinero]
        figure
          img.mb-3.img-a(src='@/assets/curso/tema_8/img_5.png', alt='Texto que describa la imagen')
          figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

    h4 Almillas o canesú

    p.mb-5 Como se mostró en la camisa infantil, una almilla o canesú, es un corte (generalmente horizontal) que se hace en el frente o en la espalda de las prendas superiores. Algunas de estas se aprovechan para dar recogido a la blusa, por ejemplo:

    .titulo-sexto.color-acento-contenido
      h5 Figura 116
      p.mb-0 #[i Blusa con canesú y recogido en frente y espalda]
    figure.mb-5
      img.mb-3.img-a(src='@/assets/curso/tema_8/img_6.png', alt='Texto que describa la imagen')
      figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

    h4 Mangas

    p.mb-0 Al igual que con las mangas de la camisa infantil, se recomienda partir de la base manga larga y sobre ésta trabajar los diferentes modelos.
    p.mb-5 Una de las variaciones más recurrentes en infantil femenino (niñas), es la manga con volumen o recogida, cabe recordar que siempre que se hará un recogido, se procede a abrir el patrón por la parte donde se dará el volumen, suavizando los ángulos y trazando un nuevo patrón, así:

    .titulo-sexto.color-acento-contenido
      h5 Figura 117
      p.mb-0 #[i Manga con recogido en copa.]
    figure.mb-5
      img.mb-3.img-a(src='@/assets/curso/tema_8/img_7.png', alt='Texto que describa la imagen')
      figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

    p.mb-5 Algunos diseños llevan recogido en ambas partes (copa y ruedo), por lo que se desprende totalmente el patrón y se da la separación para el recogido paralelamente, luego se suaviza y se traza el nuevo patrón, ver figura:

    .titulo-sexto.color-acento-contenido
      h5 Figura 118
      p.mb-0 #[i Manga con recogido en copa y ruedo.]
    figure.mb-5
      img.mb-3.img-a(src='@/assets/curso/tema_8/img_8.png', alt='Texto que describa la imagen')
      figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

    p.mb-5 Se recomienda explorar todas las opciones posibles, el éxito de un patronista depende en gran medida de su experimentación, la práctica y la creatividad.

    .cajon.color-secundario.p-4
      .row.align-items-center
        .col-lg-2
          figure
            img.img-a(src='@/assets/curso/tema_3/img_28.png', alt='Texto que describa la imagen')
        .col-lg-10
          p.mb-0 #[strong Nota:] Este tema, al igual que los demás, se puede ampliar en los manuales Patronaje y escalado línea infantil (Vélez Sánchez et al., 1995) disponible en 
            a(href="https://hdl.handle.net/11404/4874" target="_blank").link-color https://hdl.handle.net/11404/4874  
            | y Manual de patronaje básico e interpretación de diseños (Gutiérrez Rengifo et al., 2011) disponible en  
            a(href="https://hdl.handle.net/11404/4725" target="_blank").link-color https://hdl.handle.net/11404/4725. 
            | Al igual que en múltiples páginas y vídeos de patronaje.



    

</template>

<script>
export default {
  name: 'Tema8',
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
