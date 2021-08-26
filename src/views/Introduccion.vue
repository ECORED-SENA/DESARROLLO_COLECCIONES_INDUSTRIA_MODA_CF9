<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 1
      h1 Introducción al patronaje infantil
    
    p.mb-5 El patronaje se subdivide en diferentes líneas y segmentos del mercado, según la tipología de prendas de vestir a desarrollar y el público que se atiende. El patronaje infantil es el que se desarrolla para niños y adolescentes, generalmente desde la talla 2 hasta la 14 o 16, es decir entre los 2 y los 16 años de edad. Al igual que cada una de las demás líneas, la línea infantil, tiene especificaciones particulares, tales como las medidas según las tallas, la constitución corporal y las siluetas a desarrollar. En esta unidad se abordarán los conceptos fundamentales de patronaje infantil, los patrones base, algunos desarrollos y consideraciones para el futuro.

    .row.justify-content-center
      .col-lg-10

        .titulo-sexto.color-acento-contenido
          h5 Figura 1
          p.mb-0 Modelos infantiles
          
        figure
          img(src="@/assets/curso/intro.jpg", alt="Modelos infantiles")


</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped>
.introduccion
</style>
