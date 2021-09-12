<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 3
      h1 Básico de camisa de niño
    
    figure.mb-3(data-aos="flip-up")
      img.img-a(src='@/assets/curso/tema_3/img_1.png', alt='Medida lado o altura de rodilla')

    .bloque-texto-d.color-secundario.p-4.mb-5(data-aos="flip-up")
      .bloque-texto-d__texto.mb-2
        i.fas.fa-quote-left
        h3.text-regular Se llama básico de camisa a la base de prendas superiores, que como su nombre lo indica será la base con la que se construyan prendas como camisas, camisetas, suéteres, en fin, las prendas que cubren el tronco del cuerpo humano.  Para el trazo de esta base se trabajará con el Manual de patronaje básico e interpretación de diseños, por lo cual se hace importante entender las convenciones, fórmulas y métodos en él planteados.
        i.fas.fa-quote-right
      .bloque-texto-d__autor 
        .h5.mb-0 Gutiérrez Rengifo (2011)

    p.mb-5(data-aos="flip-up") Para el desarrollo de esta base se recomienda seguir el vídeo paso a paso de la base superior infantil incluido en el material complementario. 

    h3.text-center.mb-5(data-aos="flip-up") Básicos camisa de niño

    TabsB.color-acento-contenido(data-aos="flip-up")
      .py-4.py(titulo="1. Base superior infantil" :icono="require('@/assets/curso/tema_3/img_2.svg')")

        SlyderE(indicadores="derecha")
          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 1
                .list__txt    
                  h5.mb-2 Básico de corpiño
                  p Se trabaja con contorno de pecho y largo espalda o talle espalda:

      
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 24
                p.mb-0 #[i Medidas a trabajar en la base superior infantil.]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_7.png', alt='Texto que describa la imagen')
                figcaption Nota. Tomado de (Rodríguez, 2020d)

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 2
                .list__txt    
                  p Tomando la mitad del contorno de pecho, desde el centro frente, hasta el centro espalda, y el centro espalda o centro atrás para realizar el rectángulo inicial, así:

      
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 25
                p.mb-0 #[i Rectángulo inicial base superior infantil.]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_8.png', alt='Texto que describa la imagen')
                figcaption Nota. Tomado de (Rodríguez, 2020d)

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 3
                .list__txt    
                  p Trazar una línea paralela a la línea de cuello, bajando base dividido entre 4 más 0.5 cm (B/4+0.5), esta línea es la profundidad de la sisa.

                  p Hallar la mitad de esta línea y escuadrar hasta la línea de cintura, trazando así la línea de costado.
                  p Desde el centro frente (CF) hallar la tercera parte de la línea de profundidad de sisa más 0.7 cm hacia el costado, marcar y escuadrar hacia la línea de cuello o escote, esta línea es ancho pecho.

                  p Desde el centro espalda o centro atrás (CA) hallar la tercera parte de la línea de profundidad de sisa más 1.5 cm hacia el costado, marcar y escuadrar hacia la línea de cuello o escote, esta línea es ancho de espalda.

      
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 26
                p.mb-0 #[i  Proceso base superior infantil-1]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_9.png', alt='Texto que describa la imagen')
                figcaption Nota. Tomado de (Rodríguez, 2020d)

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 4
                .list__txt    
                  p Sobre la línea de cuello, desde la línea de centro frente, marcar el ancho de escotes así: contorno de pecho dividido entre 20 más 2.5 cm (B/20+2.5), y escuadrar.

                  p Dividir entre tres (3) esta medida de ancho escote, esta corresponde a la constante bola o círculo, que se emplea en adelante.

                  p Escuadrar hacia arriba (por fuera del rectángulo) desde el punto de ancho escote la constante bola o círculo y marcar el punto cuello por hombro.

      
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 27
                p.mb-0 #[i Proceso base superior infantil-2]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_10.png', alt='Texto que describa la imagen')
                figcaption Nota. Tomado de (Rodríguez, 2020d)

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 5
                .list__txt    
                  p Para encontrar la caída de hombro, bajar desde la línea de escote por la línea de ancho espalda la medida de la constante bola o círculo y escuadrar.

                  p Luego, sobre esa línea de caída de hombro salir hacia el costado la medida de la constante bola o círculo menos 0.5 cm (o-0.5).

                  p Unir con línea recta este punto con el de hombro x cuello, esta línea es el hombro:

      
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 28
                p.mb-0 #[i Proceso base superior infantil-3]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_11.png', alt='Texto que describa la imagen')
                figcaption Nota. Tomado de (Rodríguez, 2020d)

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 6
                .list__txt    
                  p Trazar con el curvígrafo la curva del escote espalda.

                  p Hallar la mitad de la línea vertical ancho de espalda, unir con recta desde el punto de hombro y con curva hasta el costado.

                  p Quedando así la espalda de la base superior infantil.
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 29
                p.mb-0 #[i Proceso base superior infantil-4]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_12.png', alt='Texto que describa la imagen')
                figcaption Nota. Tomado de (Rodríguez, 2020d)

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 7
                .list__txt    
                  p Para trazar el frente de la base, se procede de la siguiente manera:

                  p Desde el punto de centro frente (CF) por cuello, entrar la medida de contorno de pecho dividido entre 20 más 2.5 cm (B/20+2.5), medida que equivale a ancho de escote y en adelante se utilizará como la constante cuadrado (□)

                  p Desde el mismo punto de centro frente (CF) por cuello, bajar la constante cuadrado y escuadrar.
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 30
                p.mb-0 #[i Proceso base superior infantil-5]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_13.png', alt='Texto que describa la imagen')
                figcaption Nota. Tomado de (Rodríguez, 2020d)

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 8
                .list__txt    
                  p Sobre la línea de ancho pecho y desde el cuello, bajar para la caída de hombro la medida de la constante cuadro más 1 cm (□+1) y escuadrar.

                  p Desde el ancho de escote y sobre la línea de caída de hombro, aplicar la medida de hombro espalda y trazar la línea de hombro frente.
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 31
                p.mb-0 #[i Proceso base superior infantil-6]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_14.png', alt='Texto que describa la imagen')
                figcaption Nota. Tomado de (Rodríguez, 2020d)

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 9
                .list__txt    
                  p Sobre la línea de profundidad de sisa, hallar la mitad entre centro frente (CF) y ancho de pecho, marcar y escuadrar hasta la línea de cintura, esta línea es la línea de pinza.

                  p Con el fin de recuperar el talle delantero, prolongar hacia abajo (fuera del cuadro) la constante bola o círculo menos 0.5 cm (o-0.5) sobre las líneas de centro frente (CF) y de pinza desde la cintura, unir en línea recta estos puntos entre sí y con el punto de cintura por costado de la espalda.
              .titulo-sexto.color-acento-contenido
                h5 Figura 32
                p.mb-0 #[i Proceso base superior infantil-7]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_15.png', alt='Texto que describa la imagen')
                figcaption Nota. Tomado de (Rodríguez, 2020d)

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 10
                .list__txt    
                  p Para trazar las curvas del frente se procede de la siguiente manera:

                  p Escuadrar el punto de escote por hombro con respecto al hombro, con la ayuda del curvígrafo trazar la curva del escote.

                  p Hallar la mitad de la línea de ancho pecho (vertical) entre la profundidad de sisa y la caída de hombro, unir con línea recta este punto con el punto externo del hombro (hombro x sisa) y terminar con curva hasta la línea de profundidad de sisa.
              .titulo-sexto.color-acento-contenido
                h5 Figura 33
                p.mb-0 #[i Proceso base superior infantil-8]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_16.png', alt='Texto que describa la imagen')
                figcaption Nota. Tomado de (Rodríguez, 2020d)

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 11
                .list__txt    
                  p Quedando así la base superior infantil:
            .col-md-6.mb-4.mb-md-0
              .titulo-sexto.color-acento-contenido
                h5 Figura 34
                p.mb-0 #[i Final base superior infantil.]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_17.png', alt='Texto que describa la imagen')
                figcaption Nota. Tomado de (Rodríguez, 2020d)

      .py-4.py-md-5(titulo="2. Base de Manga" :icono="require('@/assets/curso/tema_3/img_3.svg')")

        SlyderE(indicadores="derecha")
          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 1
                .list__txt    
                  p Para trazar la manga es necesario tener la medida de la sisa (frente y espalda), la cual se debe tomar con la cinta métrica sobre la línea de sisa, llevándola acostada y girándola a medida que recorre la línea, como lo muestra la figura.
      
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 35
                p.mb-0 #[i Toma de medidas curvas con cinta métrica.]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_18.png', alt='Texto que describa la imagen')

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 2
                .list__txt    
                  p Trazar una línea vertical con la medida del largo manga o largo de brazo (línea de centro de manga), algunos patronistas hacen la diferencia entre estas medidas, ya que el largo de brazo es la medida tal cual se toma de la persona y el largo manga tiene adicionado el desahogo u holgura, por lo cual se recomienda trabajar con el largo de manga.
      
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 36
                p.mb-0 #[i Pasos base de manga infantil-1]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_19.png', alt='Texto que describa la imagen')
                figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.
          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 3
                .list__txt    
                  p Desde el punto superior, sobre la línea de centro frente, marcar 1/4 de contorno total de sisa (sumar sisa frente más sisa espalda), escuadrar a ambos lados y trazar una línea de apoyo o guía, llamada altura de copa de manga.
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 37
                p.mb-0 #[i Pasos base de manga infantil-2]
              figure
                img.img-a.mb-3(src='@/assets/curso/tema_3/img_20.png', alt='Texto que describa la imagen')
                figcaption Pasos base de manga infantil-2
          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 4
                .list__txt    
                  p Desde el punto superior y hasta la línea de altura de copa, marcar diagonalmente la medida de la mitad (1/2) de contorno sisa, hallando los puntos del ancho de manga. 
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 38
                p.mb-0 #[i Pasos base de manga infantil-3]
              figure
                img.img-a.mb-3(src='@/assets/curso/tema_3/img_21.png', alt='Texto que describa la imagen')
                figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 5
                .list__txt    
                  p.mb-0 Dividir en cuatro partes iguales cada una de las diagonales. 
                  p.mb-0 En el primer cuarto de cada lado, escuadrar hacia afuera 1 cm.
                  p.mb-0 En el último cuarto del frente escuadrar hacia adentro 1 cm. 
                  p.mb-0 En el último cuarto de la espalda escuadrar hacia adentro 1,2 cm.
                  p Trazar curva de copa de manga o sisa de manga, formando curva suave.
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 39
                p.mb-0 #[i Pasos base de manga infantil-4]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_22.png', alt='Texto que describa la imagen')
                figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 6
                .list__txt    
                  p Desde el punto inferior de la línea de centro, escuadrar y trazar a cada lado, la mitad de la medida de puño (ver cuadro de tallas) y unir con línea recta con el punto de ancho de manga de cada lado, así.
            .col-md-6
              .row
                .col-lg-6
                  .titulo-sexto.color-acento-contenido.mb-5
                    h5 Figura 40
                    p.mb-0 #[i Pasos base de manga infantil-5]
                  figure
                    img.img-a(src='@/assets/curso/tema_3/img_23.png', alt='Texto que describa la imagen')
                    figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.
                .col-lg-6
                  .titulo-sexto.color-acento-contenido
                    h5 Figura 41
                    p.mb-0 #[i Base manga infantil-a]
                  p.text-center.text-small.my-0 Quedando así, la base de manga infantil:
                  figure
                    img.img-a(src='@/assets/curso/tema_3/img_24.png', alt='Texto que describa la imagen')
                    figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 7
                .list__txt    
                  p Para los diferentes largos de las mangas, se emplea la base de manga, comenzando siempre por la manga larga y sobre ésta se trazan los diferentes largos así: dividir en cuatro (4) partes iguales la línea de centro de manga desde la línea de altura de copa a la línea de bajo o ruedo, encuadrar cada una de estas marcas hacia los costados de la manga hallando los diferentes largos.
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 42
                p.mb-0 #[i Pasos base de manga infantil-6]
              figure.mb-4
                img.img-a.mb-3(src='@/assets/curso/tema_3/img_25.png', alt='Texto que describa la imagen')
                figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.
              .titulo-sexto.color-acento-contenido
                h5 Figura 43
                p.mb-0 #[i Base manga infantil-b.]
              figure
                img.img-a.mb-3(src='@/assets/curso/tema_3/img_26.png', alt='Texto que describa la imagen')
                figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 8
                .list__txt    
                  p Para los diferentes largos de las mangas, se emplea la base de manga, comenzando siempre por la manga larga y sobre ésta se trazan los diferentes largos así: Dividir en cuatro (4) partes iguales la línea de centro de manga desde la línea de altura de copa a la línea de bajo o ruedo, encuadrar cada una de estas marcas hacia los costados de la manga hallando los diferentes largos.
              .cajon.color-secundario.p-4
                .row.align-items-center
                  .col-lg-2
                    figure
                      img.img-a(src='@/assets/curso/tema_3/img_28.png', alt='Texto que describa la imagen')
                  .col-lg-10
                    p.mb-0 #[strong Nota:] es importante tener en cuenta que la manga debe corresponder al contorno de sisa, por lo tanto, si se hacen modificaciones al patrón base, se deben hacer los respectivos ajustes al patrón de la manga.

            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 44
                p.mb-0 #[i Largos de mangas]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_27.png', alt='Texto que describa la imagen')
                figcaption Fuente: elaboración propia en softwares Optitex e Illustrator.

      .py-4.py.mb-0(titulo="3. Base de camisa infantil" :icono="require('@/assets/curso/tema_3/img_4.svg')")

        SlyderE(indicadores="derecha")
          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 1
                .list__txt    
                  p El primer paso para el desarrollo de la base de camisa es la asignación o aumento de los desahogos u holguras.
                  p Para el caso se trabajará con un desahogo de 6 cm, el cual corresponde a una prenda semi-holgada o floja. Por lo tanto, al trabajar sobre una prenda en cuartos, se divide entre cuatro, así: 6/4=1,5. es decir, a cada patrón se le incrementará en costado la medida de 1,5 cm.
      
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 45
                p.mb-0 #[i Pasos camisa infantil-1]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_29.png', alt='Texto que describa la imagen')
                figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 2
                .list__txt    
                  p Siempre que se dan desahogos a las partes superiores, es recomendable dar un poco de holgura al contorno de sisa, por lo cual se baja la misma medida o la mitad del desahogo parcial, es decir se trabaja (para el caso del ejemplo) con 1,5 cm o 0,75 cm. A continuación, se muestra este paso con 0.75 cm: 
      
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 46
                p.mb-0 #[i Pasos camisa infantil-2]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_30.png', alt='Texto que describa la imagen')
                figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 3
                .list__txt    
                  p Una vez se tiene la base superior con desahogos, se procede a dar el largo de camisa o largo de blusa (según cuadro de medidas), ya que la base superior infantil solo llega hasta el talle, es decir, la cintura y las camisas llegan más abajo y, generalmente, hasta la altura de cadera, aplicar largo de blusa desde hombro por escote en el frente e igualar este largo con la espalda.
                  p En este punto, es importante rectificar que la medida de contorno inferior, corresponde a la medida de contorno de cadera, pues la prenda deberá poder cerrarse a esta altura sobre el niño o la niña, como en la tabla de medidas contorno de pecho y contorno de cadera tienen la misma medida, se puede proseguir con el desarrollo, en caso de que la tabla de medidas a emplear tenga mayor dimensión para el contorno de cadera se deberá rectificar.
      
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 47
                p.mb-0 #[i Pasos camisa infantil-3]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_31.png', alt='Texto que describa la imagen')
                figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 4
                .list__txt    
                  p Es común que las camisas terminen en una curvatura en el ruedo o bajo, esto con el fin de dar mayor performance a la prenda, esta curvatura varía mucho entre marcas, líneas de vestuario y tipo de prenda, para el ejemplo se hará con una altura de 2,5 cm en costado, se encuadrara 2,5 cm hacia el centro y se trazará con el curvígrafo en dos pasos, formando una onda o ese.
      
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 48
                p.mb-0 #[i Pasos camisa infantil-4]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_32.png', alt='Texto que describa la imagen')
                figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 5
                .list__txt    
                  p La base de camisa lleva almilla o canesú en la espalda, la cual es una pieza que se usa para encarterar el frente por el hombro y la espalda, quedando así ocultas dichas costuras y proporcionando mayor comodidad al usuario. Para su desarrollo se marca en el centro espalda la altura deseada para la almilla o según diseño (ficha técnica), se escuadra hasta la sisa, en caso de no tener esta medida se puede trabajar con la tercera parte de la altura entre el punto de sisa por hombro y el punto de costado por sisa, así:
      
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 49
                p.mb-0 #[i Pasos camisa infantil-5]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_33.png', alt='Texto que describa la imagen')
                figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 6
                .list__txt    
                  p La almilla cuenta con el hombro adelantado, es decir, la línea de hombro se traslada hacia el frente, esto con el fin de que la camisa no quede tirante hacia la espalda. Para su desarrollo se traza el adelanto de hombro (paralelo a la línea de hombro) según lo deseado o el diseño a desarrollar, se corta por esta línea y se une por el hombro con la espalda, es muy importante prestar mucha atención al unir esta pieza, que el escote coincida con el escote y la sisa con la sisa. 
      
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 50
                p.mb-0 #[i Pasos camisa infantil-6]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_34.png', alt='Texto que describa la imagen')
                figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 7
                .list__txt    
                  p Otra característica principal de la camisa es su abertura en el eje frontal, en donde van los botones, broches o el sistema de cierre que se solicite en el diseño, esta abertura se llama perilla y puede ir incorporada (hace parte de la misma prenda) o independiente (se corta aparte). 

                  p Para el desarrollo de la perilla es importante tener en cuenta que el centro frente es el eje de botones, es decir, la línea por la cual se pegarán los botones y se harán los ojales, a partir de esta línea se aumenta la mitad del ancho de perilla (según diseño) a cada lado, luego, sobre la línea del extremo se aplica paralelamente el ancho de perilla (puesto que la perilla va doble), si la perilla es incorporada sólo se le da costura al extremo, si la perilla es independiente, se corta por la línea interna y se le da costura tanto a la perilla como a la camisa.

              .cajon.color-secundario.p-4
                .row.align-items-center
                  .col-lg-2
                    figure
                      img.img-a(src='@/assets/curso/tema_3/img_28.png', alt='Texto que describa la imagen')
                  .col-lg-10
                    p.mb-0 #[strong Nota:] es fundamental tener presente desdoblar el centro de la camisa (abrir por mitad) para que la curvatura del escote continúe y de esta manera no quede tirante
      
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 51
                p.mb-0 #[i Pasos camisa infantil-7]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_35.png', alt='Texto que describa la imagen')
                figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 8
                .list__txt    
                  p El cuello, es otra de las características principales de esta prenda, aun cuando existen múltiples diseños o tipos de cuellos, hay un cuello que es el más básico o clásico, el cuello camisero con banda incluida, para su desarrollo se hace un rectángulo de la mitad de contorno de escote (desde el centro espalda, hasta el cruce de botones) más 1 cm para desahogo, por el ancho de cuello (incluida banda o pie de cuello), este ancho varía entre 9 cm a 12 cm, según el diseño, para el ejemplo se trabajará con 10 cm. Marcar el centro atrás (CA) en una de las líneas verticales, el centro frente (CF) en la otra línea vertical y base de cuello en la línea inferior, ver imagen:
      
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 52
                p.mb-0 #[i Pasos camisa infantil-8]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_36.png', alt='Texto que describa la imagen')
                figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 9
                .list__txt    
                  p Desde el vértice inferior de CA y la base de cuello, subir sobre CA la medida el ancho de banda (según diseño), para el ejemplo se trabajará con 4.5 cm, escuadrar hasta el CF.
      
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 53
                p.mb-0 #[i Pasos camisa infantil-9]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_37.png', alt='Texto que describa la imagen')
                figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 10
                .list__txt    
                  p Extender la banda por el CF la medida de la mitad de ancho de perilla, encuadrar y dar forma a la esquina según el diseño, generalmente va redondeada, también en diagonal o incluso se puede dejar así rectangular. 
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 54
                p.mb-0 #[i Pasos camisa infantil-10]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_38.png', alt='Texto que describa la imagen')
                figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 11
                .list__txt    
                  p Dividir en cuatro partes iguales la línea de la base del cuello, en el cuarto hacía CF escuadrar hacia abajo 0.75 cm, sobre la línea CA subir 0.75 cm. Trazar onda suave (base del cuello), desde el nuevo punto de CA, pasando por el punto de la mitad de la base, el punto nuevo y llegando al extremo de la banda, como lo muestra la imagen.
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 55
                p.mb-0 #[i Pasos camisa infantil-11]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_39.png', alt='Texto que describa la imagen')
                figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 12
                .list__txt    
                  p En el extremo superior del CA bajar 1cm y escuadrar hacia adentro aproximadamente 2 cm (esta línea es de apoyo), en el extremo superior del CF escuadrar hacia afuera 1 cm (punto externo de la solapa). Unir con curva suave el punto de CA y el punto de solapa. Unir con línea recta el punto de solapa y el punto de CF por ancho de banda.
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 56
                p.mb-0 #[i Pasos camisa infantil-12]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_40.png', alt='Texto que describa la imagen')
                figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 13
                .list__txt    
                  p Quedando así la base de cuello camisero, va doble por el CA, se corta dos veces en el tejido principal y una vez en la entretela:
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 57
                p.mb-0 #[i Cuello camisero]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_41.png', alt='Texto que describa la imagen')
                figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 14
                .list__txt    
                  p Las camisas clásicas llevan un bolsillo de parche en el frente izquierdo, para desarrollarlo se marca sobre el frente y copia en un papel nuevo, en el que se dan las márgenes de costura, recordar marcar los puntos de plantilla donde irá pegado sobre el frente. 
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 58
                p.mb-0 #[i Boslillo]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_42.png', alt='Texto que describa la imagen')
                figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 15
                .list__txt    
                  p Al dar desahogo al cuerpo de la prenda, se debe dar a la manga, ya que el contorno de sisa de la prenda aumentó, para ello se rectifica el contorno de sisa de la manga, lo cual modifica el ancho de manga, ver figura:
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 59
                p.mb-0 #[i  Modificaciones manga-1]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_43.png', alt='Texto que describa la imagen')
                figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 16
                .list__txt    
                  p.mb-0 La camisa clásica manga larga lleva puño, por lo cual se hacen las siguientes modificaciones en el bajo: 
                  p Trazar una paralela al bajo con la medida del ancho de puño (según diseño), Ver imagen.
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 60
                p.mb-0 #[i   Modificaciones manga-2]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_44.png', alt='Texto que describa la imagen')
                figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 17
                .list__txt    
                  p Marcar la mitad entre el centro de manga y el costado (en la parte posterior de la manga), escuadrar hacia arriba y marcar la abertura de manga según diseño, para el ejemplo se trabajará con 7 cm. 

                  p Recordar que siempre que se hace un corte se debe aumentar la ventaja de costura, ver imagen.
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 61
                p.mb-0 #[i Modificaciones manga-3]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_45.png', alt='Texto que describa la imagen')
                figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 18
                .list__txt    
                  p Si la manga lleva pliegues aumentar el ancho de la medida de ancho de pliegue o pliegues (según diseño), y marcar piquetes para su doblado, si la profundidad del pliegue es de 1 cm se dan 2 cm de aumento, se marca el piquete inicial, el centro del pliegue y el piquete final.
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 62
                p.mb-0 #[i Modificaciones manga-4]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_46.png', alt='Texto que describa la imagen')
                figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 19
                .list__txt    
                  p Puño. Realizar un rectángulo con la medida inicial del ancho de puño, más la medida de monte de puño (va entre 3 y 4 cm, según diseño), más 2 cm de ventaja de costura (1cm a cada lado), el ancho de puño más ventajas de costura. El puño se corta dos veces en tela principal (uno para cada manga), dos veces en tela interna para contraste (según diseño) y dos veces en entretela, ver figura.
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 63
                p.mb-0 #[i Modificaciones manga-6]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_47.png', alt='Texto que describa la imagen')
                figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.

          .row
            .col-md-6.mb-4.mb-md-0
              .list
                .list__item
                    .list__item__bulletNumber 
                      span 20
                .list__txt    
                  p Quedando así las diferentes piezas de la camisa:

              .cajon.color-secundario.p-4
                .row.align-items-center
                  .col-lg-2
                    figure
                      img.img-a(src='@/assets/curso/tema_3/img_28.png', alt='Texto que describa la imagen')
                  .col-lg-10
                    p.mb-0 #[strong Nota:] tener presente siempre darles a los patrones los aumentos o ventajas de costura según la operación de confección a realizar Publicar en caja de texto y acompañar con la imagen que se ha utilizado en el programa para recordar datos importantes.
            .col-md-6
              .titulo-sexto.color-acento-contenido
                h5 Figura 64
                p.mb-0 #[i Camisa Infantil]
              figure
                img.img-a(src='@/assets/curso/tema_3/img_48.png', alt='Texto que describa la imagen')
                figcaption Nota. Fuente: elaboración propia en softwares Optitex e Illustrator.



</template>

<script>
export default {
  name: 'Tema3',
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
