<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 Cuadro de tallas
    
    p.mb-5 Siempre que se aborda una línea de patronaje se comienza por la construcción o el análisis de los cuadros de tallas y medidas, en los cuales se consignan las diferentes tomas de medidas antropométricas principales para la construcción de los patrones.

    .titulo-sexto.color-acento-contenido(data-aos="fade-up-left")
      h5 Figura 2
      p.mb-0 #[i Crecimiento infantil]

    figure.mb-5(data-aos="fade-up-right")
      img(src="@/assets/curso/tema_2/img_1.png", alt="Crecimiento infantil")
      figcaption Nota.https://shutr.bz/3fUzVjC y  https://shutr.bz/3xBfOwV

    p Para la línea infantil las tallas son nombradas según la edad en años, correspondiente así la T2 a un niño o una niña de 2 años, sin embargo, esta es solo una nomenclatura de referencia, pues hay niños más pequeños o más grandes que su percentil o talla. 

    p.mb-5 Para la construcción de los cuadros de medidas se tienen en cuenta las medidas de los niños distribuidas en medidas de contornos, anchos (longitudinales horizontales) y largos (longitudinales verticales) Presentadas a continuación:

    h4.text-center.mb-5 Patronaje infantil - Contornos 

    LineaTiempoD.color-acento-contenido.mb-5(data-aos="fade-down-left")
      .row.justify-content-center(numero="1" titulo="Contorno cabeza")
        p.mb-5 Esta medida es muy importante debido a que la cabeza del bebé debe poder pasar por los escotes y puesto que la línea de bebé se complementa con accesorios para la cabeza. Se toma el perímetro de la cabeza de manera horizontal sobre las orejas y pasando por la frente.
      
        .col-lg-6
          .titulo-sexto.color-acento-contenido
            h5 Figura 3
            p #[i Medida de contorno de cabeza]
          figure
            img(src='@/assets/curso/tema_2/img_2.png', alt='Medida de contorno de cabeza')

      .row.justify-content-center(numero="2" titulo="Contorno de cuello")
        p.mb-5 Se toma el perímetro de la base del cuello, en donde se forma el pliegue de unión con el tronco del cuerpo.

        .col-lg-6
          .titulo-sexto.color-acento-contenido
            h5 Figura 4
            p #[i Medida de contorno de cuello]
          figure
            img(src='@/assets/curso/tema_2/img_3.png', alt='Medida de contorno de cuello')

      .row.justify-content-center(numero="3" titulo="Contorno de pecho")
        p.mb-5 Se toma el perímetro del pecho o tórax horizontalmente pasando por debajo de las axilas del bebé.

        .col-lg-6
          .titulo-sexto.color-acento-contenido
            h5 Figura 5
            p #[i Medida de contorno de pecho]
          figure
            img(src='@/assets/curso/tema_2/img_4.png', alt='Medida de contorno de cuello')

      .row.justify-content-center(numero="4" titulo="Contorno de cintura")
        p.mb-5 Se toma el perímetro la cintura o abdomen horizontalmente pasando por el ombligo (tomar medida con pañal puesto).

        .col-lg-6
          .titulo-sexto.color-acento-contenido
            h5 Figura 6
            p #[i Medida de contorno de cintura]
          figure
            img(src='@/assets/curso/tema_2/img_5.png', alt='Medida de contorno de cintura')

      .row.justify-content-center(numero="5" titulo="Contorno de cadera")
        p.mb-5 Se toma el perímetro la cadera horizontalmente pasando por la parte más prominente de los glúteos (tomar medida con pañal puesto).
        .col-lg-6
          .titulo-sexto.color-acento-contenido
            h5 Figura 7
            p #[i Medida de contorno de cadera]
          figure
            img(src='@/assets/curso/tema_2/img_6.png', alt='Medida de contorno de cadera')

      .row.justify-content-center(numero="6" titulo="Contorno de brazo")
        p.mb-5 Se toma el perímetro del brazo horizontalmente.
        .col-lg-6
          .titulo-sexto.color-acento-contenido
            h5 Figura 8
            p #[i Medida de contorno de brazo]
          figure
            img(src='@/assets/curso/tema_2/img_7.png', alt='Medida de contorno de brazo')

      .row.justify-content-center(numero="7" titulo="Contorno de codo")
        p.mb-5 Se toma el perímetro del codo, sobre el brazo doblado.
        .col-lg-6
          .titulo-sexto.color-acento-contenido
            h5 Figura 9
            p #[i Medida de contorno de codo]
          figure
            img(src='@/assets/curso/tema_2/img_8.png', alt='Medida de contorno de codo')

      .row.justify-content-center(numero="8" titulo="Contorno de muñeca")
        p.mb-5 Se toma el perímetro de la muñeca, sobre la unión entre el antebrazo y la mano.
        .col-lg-6
          .titulo-sexto.color-acento-contenido
            h5 Figura 10
            p #[i  Medida de contorno de muñeca]
          figure
            img(src='@/assets/curso/tema_2/img_9.png', alt='Medida de contorno de codo')

    h4.text-center.mb-5 Patronaje infantil - Longitudinales

    LineaTiempoD.color-acento-contenido.mb-5(data-aos="fade-down-left")
      .row.justify-content-center(numero="1" titulo="Estatura total")
        p.mb-5 Se toma con el bebé acostado, en posición recta desde la parte superior de la cabeza hasta la base (planta) del pie.
      
        .col-lg-6
          .titulo-sexto.color-acento-contenido
            h5 Figura 11
            p #[i Medida de estatura total]
          figure
            img(src='@/assets/curso/tema_2/img_10.png', alt='Medida de estatura total')

      .row.justify-content-center(numero="2" titulo="Talle frente")
        p.mb-5 Se toma con el bebé acostado, en posición recta desde la base de cuello por hombro hasta el centro de la cintura por el frente.
      
        .col-lg-6
          .titulo-sexto.color-acento-contenido
            h5 Figura 12
            p #[i Medida talle frente]
          figure
            img(src='@/assets/curso/tema_2/img_11.png', alt='Medida talle frente')

      .row.justify-content-center(numero="3" titulo="Talle Espalda")
        p.mb-5 Se toma con el bebé acostado, en posición recta desde la base de cuello por hombro hasta el centro de la cintura por la espalda.
      
        .col-lg-6
          .titulo-sexto.color-acento-contenido
            h5 Figura 13
            p #[i Medida talle espalda]
          figure
            img(src='@/assets/curso/tema_2/img_12.png', alt='Medida talle espalda')

      .row.justify-content-center(numero="4" titulo="Largo brazo")
        p.mb-5 Se toma desde el punto de acromion (extremo de hombro) pasando por la parte externa del brazo hasta la muñeca.
      
        .col-lg-6
          .titulo-sexto.color-acento-contenido
            h5 Figura 14
            p #[i Medida largo brazo]
          figure
            img(src='@/assets/curso/tema_2/img_13.png', alt='Medida largo brazo')

      .row.justify-content-center(numero="5" titulo="Largo a codo")
        p.mb-5 Se toma desde el punto de acromion (extremo de hombro) pasando por la parte externa del brazo hasta el codo.
      
        .col-lg-6
          .titulo-sexto.color-acento-contenido
            h5 Figura 15
            p #[i Medida larga a codo]
          figure
            img(src='@/assets/curso/tema_2/img_14.png', alt='Medida larga a codo')

      .row.justify-content-center(numero="6" titulo="Largo centro frente")
        p.mb-5 Se toma verticalmente desde el centro de escote por el frente hasta el centro de la cintura por el frente.
      
        .col-lg-6
          .titulo-sexto.color-acento-contenido
            h5 Figura 16
            p #[i Medida largo centro frente]
          figure
            img(src='@/assets/curso/tema_2/img_15.png', alt='Medida largo centro frente')

      .row.justify-content-center(numero="7" titulo="Largo centro espalda")
        p.mb-5 Se toma  verticalmente desde el centro de escote por la espalda (séptima cervical) hasta el centro de la cintura por la espalda.
      
        .col-lg-6
          .titulo-sexto.color-acento-contenido
            h5 Figura 17
            p #[i Medida largo centro espalda]
          figure
            img(src='@/assets/curso/tema_2/img_16.png', alt='Medida largo centro espalda')

      .row.justify-content-center(numero="8" titulo="Ancho de espalda u hombro a hombro")
        p.mb-5 Se toma horizontalmente de acromion a acromion.
      
        .col-lg-6
          .titulo-sexto.color-acento-contenido
            h5 Figura 18
            p #[i Medida ancho espalda]
          figure
            img(src='@/assets/curso/tema_2/img_17.png', alt='Medida ancho espalda')

      .row.justify-content-center(numero="9" titulo="Largo de hombro")
        p.mb-5 Se toma horizontalmente de acromion a acromion.
      
        .col-lg-6
          .titulo-sexto.color-acento-contenido
            h5 Figura 19
            p #[i Medida largo hombro]
          figure
            img(src='@/assets/curso/tema_2/img_18.png', alt='Medida largo hombro')

      .row.justify-content-center(numero="10" titulo="Largo de pantalón o cintura al suelo")
        p.mb-5 Se toma verticalmente desde el punto de costado por cintura, hasta el piso.
      
        .col-lg-6
          .titulo-sexto.color-acento-contenido
            h5 Figura 20
            p #[i Medida pantalón o cintura al suelo]
          figure
            img(src='@/assets/curso/tema_2/img_19.png', alt='Medida largo hombro')

      .row.justify-content-center(numero="11" titulo="Largo o altura de cadera")
        p.mb-5 Se toma verticalmente desde la cintura hasta la parte más prominente (voluminosa) de la cadera.
      
        .col-lg-6
          .titulo-sexto.color-acento-contenido
            h5 Figura 21
            p #[i Medida largo o altura de cadera]
          figure
            img(src='@/assets/curso/tema_2/img_20.png', alt='Medida largo o altura de cadera')

      .row.justify-content-center(numero="12" titulo="Largo o altura de rodilla")
        p.mb-5 Se toma verticalmente por el costado, desde la cintura hasta la rodilla.
        .col-lg-6
          .titulo-sexto.color-acento-contenido
            h5 Figura 22
            p #[i Medida largo o altura de rodilla]
          figure
            img(src='@/assets/curso/tema_2/img_21.png', alt='Medida lado o altura de rodilla')

      .row.justify-content-center(numero="13" titulo="Largo, altura o profundidad de tiro")
        p.mb-5 Se toma con el niño sentado sobre una superficie recta, con la espalda recta y las rodillas formando un ángulo recto. Tomar verticalmente por el costado, desde la cintura hasta la superficie del asiento.
        .col-lg-6
          .titulo-sexto.color-acento-contenido
            h5 Figura 23
            p #[i Medida de largo, altura o profundidad de tiro]
          figure
            img(src='@/assets/curso/tema_2/img_22.png', alt='Medida de largo, altura o profundidad de tiro')

    p.mb-5 Al ser patronaje industrial, se trabaja con medidas estandarizadas producto de estudios antropométricos en los que se miden diferentes individuos en cada una de las tallas o edades, para luego construir un cuadro de tallas con las medidas promedio y atender al público objetivo. Siempre se recomienda a los patronistas y a las marcas desarrollar sus propios estudios antropométricos y cuadros de medidas. A continuación, se presentan algunos ejemplos de cuadros de medidas:

    .row.justify-content-center.mb-5(data-aos="zoom-in-up")
      .col-lg-10
        .titulo-sexto.color-acento-contenido
          h5 Tabla 1
          p.mb-0 #[i Cuadro de tallas infantiles normalizado]
        .tabla-a.color-acento-botones.mb-5 
          table
            caption Nota. Vélez Sánchez et al. (1995)
            thead
              tr.th_bg_1.text-center
                th(colspan='2') TALLA
                th 2
                th 4
                th 6
                th 8
                th 10
                th 12
                th 14
                th 16
            tbody.text-center
              tr
                td(colspan='2') 
                  h5 Talle espalda
                td 22.5
                td 25.5
                td 28.5
                td 31.5
                td 32.5
                td 34.5
                td 36.5
                td 38.5
              tr.td_bg_1
                td(colspan='2') 
                  h5 Talle delantero
                td 24.5
                td 27.5
                td 30.5
                td 33.5
                td 34.5
                td 36.5
                td 38.5
                td 40.5
              tr
                td(colspan='2') 
                  h5 Pecho
                td 30
                td 31.5
                td 33
                td 34.5
                td 36
                td 38
                td 40.5
                td 43
              tr.td_bg_1
                td(colspan='2') 
                  h5 Cintura
                td 26
                td 27
                td 28
                td 29
                td 30
                td 31
                td 32
                td 33
              tr
                td(colspan='2') 
                  h5 Cadera
                td 30
                td 32
                td 34
                td 36
                td 38
                td 40
                td 42
                td 44
              tr.td_bg_1
                td(colspan='2') 
                  h5 Cuello
                td 23.2
                td 24.6
                td 26
                td 27.4
                td 28.8
                td 30
                td 31.3
                td 32.6
              tr
                td(colspan='2') 
                  h5 Largo hombro
                td 7.3
                td 8
                td 9
                td 9.5
                td 10
                td 11
                td 12
                td 13
              tr.td_bg_1
                td(colspan='2') 
                  h5 Ancho espalda
                td 24
                td 25
                td 27
                td 30.2
                td 32
                td 33
                td 34
                td 35
              tr
                td(colspan='2') 
                  h5 Largo vestido
                td 45
                td 50
                td 60
                td 70
                td 75
                td 80
                td 85
                td 90
              tr.td_bg_1
                td(colspan='2') 
                  h5 Largo brazo
                td 32
                td 36
                td 40
                td 44
                td 48
                td 52
                td 56
                td 60
              tr
                td(colspan='2') 
                  h5 Largo codo
                td 18.5
                td 19.5
                td 20.5
                td 21.5
                td 22.5
                td 24
                td 25.5
                td 27
              tr.td_bg_1
                td(colspan='2') 
                  h5 Contorno codo
                td 20
                td 21
                td 22
                td 23
                td 24
                td 25
                td 26
                td 27
              tr
                td(colspan='2') 
                  h5 Contorno muñeca
                td 14
                td 15
                td 16
                td 17
                td 18
                td 19
                td 20
                td 21
              tr.td_bg_1
                td(colspan='2') 
                  h5 Contorno brazo
                td 22
                td 23
                td 24
                td 25
                td 26
                td 27
                td 28
                td 29
              tr
                td(colspan='2') 
                  h5 Cintura al suelo
                td 52.5
                td 59.5
                td 66.5
                td 73.5
                td 78.5
                td 87.5
                td 94
                td 105
              tr.td_bg_1
                td(colspan='2') 
                  h5 Estatura 7 C
                td 75
                td 85
                td 95
                td 105
                td 115
                td 125
                td 135
                td 145
              tr
                td(colspan='2') 
                  h5 Estatura total
                td 87
                td 102
                td 117
                td 132
                td 142
                td 149
                td 155
                td 161
              tr.td_bg_1
                td(colspan='2') 
                  h5 Falda larga
                td 30
                td 36
                td 42
                td 46
                td 50
                td 54
                td 57
                td 60
              tr
                td(colspan='2') 
                  h5 Falda corta
                td 23
                td 25
                td 30
                td 34
                td 38
                td 40
                td 44
                td 48
              tr.td_bg_1
                td(colspan='2') 
                  h5 Base
                td 34
                td 35.5
                td 37
                td 38.5
                td 40
                td 42
                td 44.5
                td 47
              tr
                td(colspan='2') 
                  h5 Bota
                td 15.4
                td 16.6
                td 17.3
                td 18
                td 18.7
                td 19.4
                td 20.1
                td 20.8
              
    .row.justify-content-center.mb-5(data-aos="zoom-in-up")
      .col-lg-10
        .titulo-sexto.color-acento-contenido
          h5 Tabla 2
          p.mb-0 #[i Cuadro de tallas Infantil en centímetros]
        .tabla-a.color-acento-botones.mb-5 
          table
            caption Nota. (Gutiérrez Rengifo et al., 2011)
            thead
              tr.th_bg_1.text-center
                th(colspan='2') MEDIDAS
                th 2
                th 4
                th 5
                th 6
                th 7
                th 8
                th 10
                th 12
                th 14
              tr.th_bg_2
                th(colspan='2') 
                  h5.text-white ESTATURA
                th 93
                th 103
                th 108
                th 113
                th 118
                th 123
                th 133
                th 143
                th 153
            tbody.text-center
              tr 
                td(colspan='2') 
                  h5 Contorno de cadera
                td 62
                td 64
                td 66
                td 68
                td 70
                td 72
                td 76
                td 80
                td 84
              tr.td_bg_1 
                td(colspan='2') 
                  h5 Contorno de pecho
                td 62
                td 64
                td 66
                td 68
                td 70
                td 72
                td 76
                td 80
                td 84
              tr
                td(colspan='2') 
                  h5 Contorno de cintura
                td 50
                td 52
                td 54
                td 56
                td 58
                td 60
                td 64
                td 68
                td 72
              tr.td_bg_1 
                td(colspan='2') 
                  h5 Ancho de espalda
                td 25.25
                td 25
                td 25.75
                td 26.5
                td 27.25
                td 28
                td 29.5
                td 31
                td 32.5
              tr
                td(colspan='2') 
                  h5 Ancho de pecho
                td 23.25
                td 24
                td 24.75
                td 25.5
                td 26.25
                td 27
                td 28.5
                td 30
                td 31.5
              tr.td_bg_1 
                td(colspan='2') 
                  h5 Largo de talle
                td 26.5
                td 27.5
                td 28.6
                td 29.75
                td 30.82
                td 32
                td 34.25
                td 36.5
                td 38.75
              tr
                td(colspan='2') 
                  h5 Largo de costado
                td 10.25
                td 11
                td 11.75
                td 12.5
                td 13.25
                td 14
                td 15.5
                td 17
                td 18.5
              tr.td_bg_1 
                td(colspan='2') 
                  h5 Largo de centro frente
                td 21.5
                td 22.5
                td 23.5
                td 24.5
                td 25.5
                td 26.5
                td 28.5
                td 30.5
                td 32.5
              tr
                td(colspan='2') 
                  h5 Largo de centro atrás
                td 25
                td 26
                td 27.12
                td 28.25
                td 29.37
                td 30.5
                td 32.75
                td 35
                td 37.25
              tr.td_bg_1 
                td(colspan='2') 
                  h5 Largo de hombro
                td 8.75
                td 9
                td 9.25
                td 9.5
                td 9.75
                td 10
                td 10.5
                td 11
                td 11.5
              tr
                td(colspan='2') 
                  h5 Largo de pantalón
                td 60
                td 64
                td 66.5
                td 69
                td 71.5
                td 74
                td 79
                td 84
                td 89
              tr.td_bg_1 
                td(colspan='2') 
                  h5 Largo de tiro
                td 17.5
                td 18
                td 18.5
                td 19
                td 19.5
                td 20
                td 21
                td 22
                td 23
              tr
                td(colspan='2') 
                  h5 Largo de falda
                td 35
                td 37
                td 39
                td 41
                td 43
                td 45
                td 49
                td 53
                td 57
              tr.td_bg_1 
                td(colspan='2') 
                  h5 Largo de blusa
                td 44.25
                td 45
                td 45.75
                td 46.5
                td 47.25
                td 48
                td 49.5
                td 51
                td 52.5
              tr
                td(colspan='2') 
                  h5 Largo de manga
                td 35
                td 37
                td 39
                td 41
                td 43
                td 45
                td 49
                td 53
                td 57
              tr.td_bg_1 
                td(colspan='2') 
                  h5 Cabeza de manga
                td 9
                td 9.5
                td 10
                td 10.5
                td 11
                td 11.5
                td 12
                td 12.5
                td 13
              tr
                td(colspan='2') 
                  h5 Puño
                td 17.5
                td 18
                td 18.5
                td 19
                td 19.5
                td 20
                td 20.5
                td 21
                td 22
              
    .row.justify-content-center.mb-5(data-aos="zoom-in-up")
      .col-lg-10
        .titulo-sexto.color-acento-contenido
          h5 Tabla 3
          p.mb-0 #[i Tabla de medida niñas]
        .tabla-a.color-acento-botones.mb-5 
          table
            caption Nota. https://bit.ly/3ACsPrR
            thead
              tr.th_bg_1.text-center
                th(colspan='2') TALLA
                th 2
                th 4
                th 6
                th 8
                th 10
                th 12
                th 14
                th 16
            tbody.text-center
              tr
                td(colspan='2') 
                  h5 Contorno de pecho
                td 60
                td 64
                td 68
                td 72
                td 76
                td 80
                td 84
                td 88
              tr
                td(colspan='2') 
                  h5 Contorno de cintura
                td 57
                td 58
                td 59
                td 60
                td 61
                td 62
                td 63
                td 64
              tr
                td(colspan='2') 
                  h5 Contorno de cadera
                td 64
                td 68
                td 72
                td 76
                td 80
                td 84
                td 88
                td 92
              tr
                td(colspan='2') 
                  h5 Largo de espalda
                td 26
                td 28
                td 30
                td 32
                td 34
                td 36
                td 38
                td 40
              tr
                td(colspan='2') 
                  h5 Largo de sisa
                td 11.5
                td 12.5
                td 13.5
                td 14.5
                td 15.5
                td 16.5
                td 17.5
                td 18.5
              tr
                td(colspan='2') 
                  h5 Contorno cuello
                td 28
                td 29
                td 30
                td 31
                td 32
                td 33
                td 34
                td 35
              tr
                td(colspan='2') 
                  h5 Ancho de espalda
                td 23.5
                td 25
                td 26.5
                td 28
                td 29.5
                td 31
                td 32.5
                td 34
              tr
                td(colspan='2') 
                  h5 Ancho de hombro
                td 8
                td 9
                td 10
                td 11
                td 12
                td 13
                td 14
                td 15
              tr
                td(colspan='2') 
                  h5 Largo de manga
                td 32
                td 36
                td 40
                td 44
                td 48
                td 52
                td 56
                td 60
              tr
                td(colspan='2') 
                  h5 Contorno de muñeca
                td 13.5
                td 14
                td 14.5
                td 15
                td 15.5
                td 16
                td 16.5
                td 17
              tr
                td(colspan='2') 
                  h5 Largo pantalón
                td 58
                td 64
                td 70
                td 76
                td 82
                td 88
                td 94
                td 100
              tr
                td(colspan='2') 
                  h5 Largo falda
                td 42
                td 48
                td 54
                td 60
                td 66
                td 72
                td 78
                td 84
              tr
                td(colspan='2') 
                  h5 Altura de tiro
                td 14.5
                td 16
                td 17.5
                td 19
                td 20.5
                td 22
                td 23.5
                td 25
              tr
                td(colspan='2') 
                  h5 Altura de cadera 
                td 10.75
                td 12
                td 13.25
                td 14.5
                td 15.75
                td 17
                td 18.25
                td 19.5
    .row.justify-content-center.mb-5(data-aos="zoom-in-up")
      .col-lg-10
        .titulo-sexto.color-acento-contenido
          h5 Tabla 4
          p.mb-0 #[i Tabla de tallas para niños]
        .tabla-a.color-acento-botones.mb-5 
          table
            
            thead
              tr.th_bg_1.text-center
                th(colspan='9') TALLE ESPALDA - DELANTERO - MANGA NIÑO
              tr.th_bg_2
                th(colspan='2') 
                  h5.text-white TALLA
                th 1
                th 2
                th 4
                th 6
                th 8
                th 10
                th 12
            tbody.text-center
              tr 
                td(colspan='2') 
                  h5 Contorno pecho
                td.tx_bg1 54.0
                td.tx_bg2 60.0
                td.tx_bg3 64.5
                td.tx_bg4 70.0
                td.tx_bg5 73.0
                td.tx_bg6 76.0
                td.tx_bg7 80.0
              tr 
                td(colspan='2') 
                  h5 Contorno cintura
                td.tx_bg1 51.0
                td.tx_bg2 55.0
                td.tx_bg3 58.
                td.tx_bg4 62.0
                td.tx_bg5 66.0
                td.tx_bg6 70.0
                td.tx_bg7 74.0
              tr 
                td(colspan='2') 
                  h5 Holgura contorno pecho
                td.tx_bg1 8.0
                td.tx_bg2 12.0
                td.tx_bg3 12.0
                td.tx_bg4 12.0
                td.tx_bg5 12.0
                td.tx_bg6 12.0
                td.tx_bg7 10.0
              tr 
                td(colspan='2') 
                  h5 Ancho hombro
                td.tx_bg1 7.0
                td.tx_bg2 9.4
                td.tx_bg3 10.0
                td.tx_bg4 10.8
                td.tx_bg5 11.4
                td.tx_bg6 12.3
                td.tx_bg7 13.0
              tr 
                td(colspan='2') 
                  h5 Largo talle
                td.tx_bg1 27.0
                td.tx_bg2 29.2
                td.tx_bg3 33.0
                td.tx_bg4 35.0
                td.tx_bg5 38.0
                td.tx_bg6 39.0
                td.tx_bg7 39.8
              tr 
                td(colspan='2') 
                  h5 Largo manga
                td.tx_bg1 27.3
                td.tx_bg2 31.3
                td.tx_bg3 35.0
                td.tx_bg4 38.3
                td.tx_bg5 41.2
                td.tx_bg6 45.3
                td.tx_bg7 53.5
                

    .row.justify-content-center.mb-5(data-aos="zoom-in-up")
      .col-lg-10
        .tabla-a.color-acento-botones.mb-5 
          table
            caption Nota. https://bit.ly/37Bav6g
            thead
              tr.th_bg_1.text-center
                th(colspan='9') PANTALÓN NIÑO: DELANTERO - TRASERO
              tr.th_bg_2
                th(colspan='2') 
                  h5.text-white TALLA
                th 1
                th 2
                th 4
                th 6
                th 8
                th 10
                th 12
            tbody.text-center
              tr 
                td(colspan='2') 
                  h5 Contorno cintura
                td.tx_bg1 51.0
                td.tx_bg2 55.0
                td.tx_bg3 58.0
                td.tx_bg4 62.0
                td.tx_bg5 66.0
                td.tx_bg6 70.0
                td.tx_bg7 74.0
              tr 
                td(colspan='2') 
                  h5 Contorno cadera
                td.tx_bg1 62.0
                td.tx_bg2 64.0
                td.tx_bg3 69.0
                td.tx_bg4 75.0
                td.tx_bg5 79.0
                td.tx_bg6 83.1
                td.tx_bg7 88.0
              tr 
                td(colspan='2') 
                  h5 Largo rodilla
                td.tx_bg1 32.0
                td.tx_bg2 34.0
                td.tx_bg3 38.0
                td.tx_bg4 44.0
                td.tx_bg5 46.0
                td.tx_bg6 48.0
                td.tx_bg7 52.0
              tr 
                td(colspan='2') 
                  h5 Largo pantalon
                td.tx_bg1 48.0
                td.tx_bg2 50.0
                td.tx_bg3 61.0
                td.tx_bg4 70.0
                td.tx_bg5 77.0
                td.tx_bg6 85.0
                td.tx_bg7 92.0
              tr 
                td(colspan='2') 
                  h5 Contorno rodilla
                td.tx_bg1 7.0
                td.tx_bg2 7.5
                td.tx_bg3 8.0
                td.tx_bg4 8.5
                td.tx_bg5 9.0
                td.tx_bg6 9.5
                td.tx_bg7 10.0
              tr 
                td(colspan='2') 
                  h5 Contorno pantalón
                td.tx_bg1 6.0
                td.tx_bg2 6.5
                td.tx_bg3 7.0
                td.tx_bg4 7.5
                td.tx_bg5 8.0
                td.tx_bg6 8.5
                td.tx_bg7 90
              tr 
                td(colspan='2') 
                  h5 Tiro delantero
                td.tx_bg1 17.2
                td.tx_bg2 17.8
                td.tx_bg3 20
                td.tx_bg4 22
                td.tx_bg5 23.1
                td.tx_bg6 24.4
                td.tx_bg7 25.7
              tr 
                td(colspan='2') 
                  h5 Tiro trasero
                td.tx_bg1 19.4
                td.tx_bg2 20.6
                td.tx_bg3 23.2
                td.tx_bg4 26.5
                td.tx_bg5 28.4
                td.tx_bg6 29.8
                td.tx_bg7 31.9

    .row.justify-content-center.mb-5(data-aos="zoom-in-up")
      .col-lg-10
        .titulo-sexto.color-acento-contenido
          h5 Tabla 5
          p.mb-0 #[i Tabla de tallas para niñas]
        .tabla-a.color-acento-botones.mb-5 
          table
            
            thead
              tr.th_bg_1.text-center
                th(colspan='9') TALLES DELANTERO Y ESPALDA DE ÑIÑA
              tr.th_bg_2
                th(colspan='2') 
                  h5.text-white TALLA
                th 1/2
                th 2
                th 4
                th 6
                th 8
                th 10
                th 12
            tbody.text-center
              tr 
                td(colspan='2') 
                  h5 Contorno pecho
                td.tx_bg1 47.0
                td.tx_bg2 57.0
                td.tx_bg3 59.0
                td.tx_bg4 64.0
                td.tx_bg5 68.5
                td.tx_bg6 74.0
                td.tx_bg7 78.0
              tr 
                td(colspan='2') 
                  h5 Contorno cintura
                td.tx_bg1 50.0
                td.tx_bg2 50.2
                td.tx_bg3 52.0
                td.tx_bg4 54.4
                td.tx_bg5 59.6
                td.tx_bg6 63.0
                td.tx_bg7 68.6
              tr 
                td(colspan='2') 
                  h5 Ancho hombro
                td.tx_bg1 6.2
                td.tx_bg2 7.7
                td.tx_bg3 8.6
                td.tx_bg4 8.9
                td.tx_bg5 9.6
                td.tx_bg6 10.2
                td.tx_bg7 10.6
              tr 
                td(colspan='2') 
                  h5 Largo talle
                td.tx_bg1 21.0
                td.tx_bg2 25.3
                td.tx_bg3 28.6
                td.tx_bg4 31.1
                td.tx_bg5 33.2
                td.tx_bg6 36.2
                td.tx_bg7 39.0
              tr 
                td(colspan='2') 
                  h5 Largo manga
                td.tx_bg1 23.0
                td.tx_bg2 26.5
                td.tx_bg3 33.0
                td.tx_bg4 38.0
                td.tx_bg5 44.0
                td.tx_bg6 50.0
                td.tx_bg7 56.0

    .row.justify-content-center.mb-5(data-aos="zoom-in-up")
      .col-lg-10
        .tabla-a.color-acento-botones.mb-5 
          table
            
            thead
              tr.th_bg_1.text-center
                th(colspan='8') FALDAS DELANTERO Y TRASERO NIÑA
              tr.th_bg_2
                th(colspan='2') 
                  h5.text-white TALLA
                th 2
                th 4
                th 6
                th 8
                th 10
                th 12
            tbody.text-center
              tr 
                td(colspan='2') 
                  h5 Contorno cintura
                td.tx_bg2 50.20
                td.tx_bg3 52.00
                td.tx_bg4 54.40
                td.tx_bg5 59.60
                td.tx_bg6 63.00
                td.tx_bg7 68.60
              tr 
                td(colspan='2') 
                  h5 Contorno cadera
                td.tx_bg2 64.00
                td.tx_bg3 69.00
                td.tx_bg4 75.00
                td.tx_bg5 79.00
                td.tx_bg6 83.00
                td.tx_bg7 88.00
              tr 
                td(colspan='2') 
                  h5 Largo cadera
                td.tx_bg2 7.20
                td.tx_bg3 9.20
                td.tx_bg4 11.50
                td.tx_bg5 13.50
                td.tx_bg6 15.70
                td.tx_bg7 18.00
              tr 
                td(colspan='2') 
                  h5 Largo rodilla
                td.tx_bg2 19.50
                td.tx_bg3 26.00
                td.tx_bg4 33.20
                td.tx_bg5 41.50
                td.tx_bg6 48.20
                td.tx_bg7 55.50

    .row.justify-content-center.mb-5(data-aos="zoom-in-up")
      .col-lg-10
        .tabla-a.color-acento-botones.mb-5 
          table
            caption Nota. https://bit.ly/3yFduq9
            thead
              tr.th_bg_1.text-center
                th(colspan='9') PANTALÓN NIÑA DELANTERO / TRASERO
              tr.th_bg_2
                th(colspan='2') 
                  h5.text-white TALLA
                th 1/2
                th 2
                th 4
                th 6
                th 8
                th 10
                th 12
            tbody.text-center
              tr 
                td(colspan='2') 
                  h5 Contorno cintura
                td.tx_bg1 49.0
                td.tx_bg2 50.0
                td.tx_bg3 52.0
                td.tx_bg4 54.4
                td.tx_bg5 59.6
                td.tx_bg6 63.0
                td.tx_bg7 68.0
              tr 
                td(colspan='2') 
                  h5 Contorno cadera
                td.tx_bg1 62.0
                td.tx_bg2 64.0
                td.tx_bg3 69.0
                td.tx_bg4 75.0
                td.tx_bg5 79.0
                td.tx_bg6 83.0
                td.tx_bg7 88.0
              tr 
                td(colspan='2') 
                  h5 Largo rodilla
                td.tx_bg1 32.0
                td.tx_bg2 34.0
                td.tx_bg3 36.0
                td.tx_bg4 44.0
                td.tx_bg5 46.6
                td.tx_bg6 48.0
                td.tx_bg7 52.0
              tr 
                td(colspan='2') 
                  h5 Largo pantalón
                td.tx_bg1 48.0
                td.tx_bg2 50.0
                td.tx_bg3 60.0
                td.tx_bg4 68.0
                td.tx_bg5 76.0
                td.tx_bg6 84.0
                td.tx_bg7 92.0
              tr 
                td(colspan='2') 
                  h5 Contorno rodilla
                td.tx_bg1 7.2
                td.tx_bg2 7.7
                td.tx_bg3 8.2
                td.tx_bg4 8.7
                td.tx_bg5 9.2
                td.tx_bg6 9.7
                td.tx_bg7 10.2
              tr 
                td(colspan='2') 
                  h5 Contorno pantalón
                td.tx_bg1 6.0
                td.tx_bg2 6.5
                td.tx_bg3 7.0
                td.tx_bg4 7.5
                td.tx_bg5 8.0
                td.tx_bg6 8.5
                td.tx_bg7 9.0
              tr 
                td(colspan='2') 
                  h5 Tiro delantero
                td.tx_bg1 16.4
                td.tx_bg2 17
                td.tx_bg3 19.8
                td.tx_bg4 23.6
                td.tx_bg5 25.4
                td.tx_bg6 26.7
                td.tx_bg7 28.0
              tr 
                td(colspan='2') 
                  h5 Tiro trasero
                td.tx_bg1 20.0
                td.tx_bg2 20.0
                td.tx_bg3 23.1
                td.tx_bg4 27.2
                td.tx_bg5 29.3
                td.tx_bg6 30.2
                td.tx_bg7 31.7

    p(data-aos="zoom-in-up") Para el trazo de los patrones de esta unidad se trabajará con el cuadro de Cuadro de tallas para bebé normalizado, tomado de Patronaje y escalado línea infantil de Vélez Sánchez et al. (1995)

</template>

<script>
export default {
  name: 'Tema2',
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
