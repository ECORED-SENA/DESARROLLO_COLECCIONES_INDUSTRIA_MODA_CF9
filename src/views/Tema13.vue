<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 13
      h1 Básico de chaqueta

    p(data-aos="flip-up") La chaqueta es una prenda de abrigo, que, al ir sobrepuesta a las demás prendas, es decir, ser una capa exterior superior, requiere de desahogos u holguras mayores, se puede realizar partiendo de la base superior, en caso de ser corta; de la base de camisa infantil, en caso de ser recta (no entallada); de la base de blusa infantil, en caso de ser entallada; e incluso en algunos casos se puede trabajar con el básico de vestido, si es, por ejemplo, un abrigo.
    p.mb-5 Para su desarrollo se procede de la misma manera que se trabajaron los básicos de camisa y de blusa, aumentando los desahogos para dar la capacidad de vestir sobre las demás prendas, es importante tener en cuenta que si se parte de la blusa o de la camisa, estas ya tienen desahogos, por lo tanto se recomienda dar los desahogos sobre estos, si se parte de la base superior (base sin desahogos) se darán completos los desahogos, o sea, si el desahogo que se trabajará es de 12cm en total y la base de camisa tiene 6cm, éstos se le restará a la base de chaqueta, quedando un total de 6cm a dar, dividido entre 4 se dará un desahogo de 1.5cm en cada costado, 0.75cm en la altura de sisa, 0.75 en ancho de espalda y 0.75 en contorno de escote (con el fin de que se dé capacidad al cuello de la camisa). Ver figura

    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-lg-8
        .titulo-sexto.color-acento-contenido
          h5 Figura 147
          p.mb-0 #[i Base de chaqueta infantil]
        figure
          img.img-a(src='@/assets/curso/tema_12/img_7.png', alt='Texto que describa la imagen')
          figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator

    p.text-center Así mismo, se realizan las demás bases. Se exhorta a que el aprendiz explore diferentes caminos y encuentre soluciones a cada desarrollo.

   
   


</template>

<script>
export default {
  name: 'Tema13',
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
