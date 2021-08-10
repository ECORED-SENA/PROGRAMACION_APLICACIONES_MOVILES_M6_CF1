<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero
        span 1
      h1 	Enfoque metodológico para el desarrollo de aplicaciones móviles nativas
    .row.mt-5
      .col-12.col-lg-7
        p Actualmente, las metodologías ágiles tienen una gran notoriedad, ya que instituyen una buena solución para desarrollar proyectos en tiempos más cortos, en especial aquellos proyectos que constantemente presentan cambios es sus requisitos, las aplicaciones para dispositivos móviles son un buen ejemplo de esto ya que requieren una variedad de características como: portabilidad, movilidad, adaptación  entre otras, y aunque se encuentran muchas aplicaciones para dispositivos móviles que corren en diferentes plataformas, no llenan totalmente las expectativas de los usuarios debido a su baja calidad en el desarrollo, esto debido a que  el uso de metodologías no son una prioridad  en este tipo de aplicaciones, ignorando los métodos de ingeniería que son los que garantizan la mantenibilidad y calidad de las aplicaciones.
      .col-4.col-lg-5.offset-4.offset-lg-0.align-self-center
        figure
          img(src="@/assets/template/tema-1-1.png", alt="Texto que describa la imagen")
    .row.mt-5
      .col-10.col-lg-8.offset-1.offset-lg-2
        .bloque-texto-a.color-acento-botones-invertido.bg-acento-botones.p-4.p-md-4.mb-5 
          .row.m-0.align-items-center.justify-content-between
            .col-lg-8
              .bloque-texto-a__texto.p-4
                .h4.mb-0.text-small Según con Letelier y Canos (2003)
                p.text-small Teniendo en cuenta lo anterior y que las metodologías ágiles son procesos para desarrollar <i>software</i> de manera rápida y con gran facilidad de adopción por los equipos de trabajo se han seleccionado las metodologías ágiles más referenciadas para emplearlas en el desarrollo de aplicaciones móviles, estas son muy convenientes teniendo en cuenta como han venido creciendo los proyectos para estas tecnologías.
            .col-lg-4.mb-4.mb-lg-0
              figure
                img(src="@/assets/template/tema-1-2.svg", alt="Texto que describa la imagen")
    p.mt-5 A continuación, se describen conceptos principales para la introducción al uso de metodologías de desarrollo.
    .row.mt-5 
      .col-10.offset-1
        .cajon.color-primario.p-4.mb-4.bg-primario-op50
          .row
            .col-2.d-none.d-lg-block
              figure
                img(src="@/assets/template/tema-1-3.svg", alt="Texto que describa la imagen")
            .col-12.col-lg-10
              .h4.mb-0 La metodología según  Avison y Fitzgerald (2006)
              p Contribuye en la implementación de nuevos sistemas de información utilizando un conjunto de métodos, herramientas y documentos auxiliares, una metodología se divide en fases y subfases, para planificar, gestionar y controlar el proyecto, también permiten seleccionar las técnicas más indicadas en cada proceso de un proyecto.
    .row.mt-4 
      .col-10.offset-1
        .cajon.color-primario.p-4.mb-4.bg-primario-op30
          .row
            .col-2.d-none.d-lg-block
              figure
                img(src="@/assets/template/tema-1-4.svg", alt="Texto que describa la imagen")
            .col-12.col-lg-10
              .h4.mb-0 La metodología ágil según Amaya Balaguera (2015)
              p Estas metodologías surgen como una alternativa a las metodologías tradicionales, su enfoque viene de los principios del manifiesto ágil que se basan en un desarrollo iterativo, su objetivo principal se centra en realizar una mejor captura de los requisitos cambiantes, la gestión de riesgos y la reducción del tiempo de desarrollo. 
    p.mt-4 Entre las principales metodologías ágiles para ser aplicadas en el desarrollo de aplicaciones móviles se presentan las siguientes:
    .row.mt-4 
      .col-10.offset-1
        .cajon.color-primario.p-4.mb-4.bg-primario-op15
          .row
            .col-2.d-none.d-lg-block
              figure
                img(src="@/assets/template/tema-1-5.svg", alt="Texto que describa la imagen")
            .col-12.col-lg-10
              .h4.mb-0 Extreme Programing (XP) Beck & Zapata Martínez (2002)
              p Lo define como una metodología liviana que se puede utilizar en grupos de desarrollo pequeños y medianos que se centra en los requerimientos no exactos y continuamente cambiantes Se caracteriza por tener un ciclo de vida dinámico mediante ciclos de desarrollo cortos llamados iteraciones. Sus fases son análisis diseño, desarrollo y pruebas en las que aplica 12 prácticas.
    .row.mt-5
      .col-10.offset-1
        .h4 Figura 1
        p Prácticas de XP
        figure.mt-4
          img(src="@/assets/template/tema-1-6.png", alt="Texto que describa la imagen")
      p.mt-5 Así pues, XP no es un conjunto de técnicas solamente, sino un conjunto de principios probados y fiables con características de las metodologías convencionales pero llevadas a un nivel extremo. 
    .row.mt-5
      .col-10.offset-1
        .tarjeta.color-primario.p-3.mb-5.bg-azul-degradado
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-2
              img(src="@/assets/template/tema-1-7.svg").w-75.margin-0-auto
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0.text-white
                  h2.mb-1 Metodología ágil XP
                  p.font-16.p-0 A continuación, puede ampliar información sobre la metodología ágil XP. Video sobre ciclo de vida XP, prácticas básicas de XP:
                .col-sm-auto
                  a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=tCl33R9jHBk" target="_blank")
                    span.font-16 Enlace web
                    i.fas.fa-link
    figure.mt-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/9MaFAIVuGVY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    .row.mt-5 
      .col-10.offset-1
        .cajon.color-acento-botones.p-4.mb-4.bg-acento-botones-op50
          .row
            .col-2.d-none.d-lg-block
              figure
                img(src="@/assets/template/tema-1-8.svg", alt="Texto que describa la imagen")
            .col-12.col-lg-10
              .h4.mb-0 Scrum. De acuerdo a Takeuchi & Nonaka (1986)
              p Presenta un proceso adaptativo, rápido y auto-organizado de desarrollo de productos, y se centra en la gestión de proyectos en situaciones difíciles de planificar al futuro. La palabra <i>Scrum</i> viene del famoso juego de rugby y hace referencia a cómo se devuelve un balón que ha salido del campo al terreno del juego de una manera colectiva.
    p.mt-5 Este modelo se encuentra basado en lo que es el desarrollo incremental, es decir conforme pasen las fases y la iteración mayor va a ser el tamaño del proyecto que se está desarrollando.
    .h4.mt-5 Los procesos que utiliza son: 
    .row.mt-5
      .col-sm.mb-5.mb-sm-0
        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta.acento-botones
              span 1
            | <i>Product Backlog</i>
          li 
            .lista-ol--cuadro__vineta.acento-botones
              span 2
            | <i>Sprint Backlog</i>
          li 
            .lista-ol--cuadro__vineta.acento-botones
              span 3
            | <i>Sprint Planning Meeting</i>
          li 
            .lista-ol--cuadro__vineta.acento-botones
              span 4
            | <i>Daily Scrum</i>
          li 
            .lista-ol--cuadro__vineta.acento-botones
              span 5
            | <i>Sprint Review</i>
          li 
            .lista-ol--cuadro__vineta.acento-botones
              span 6
            | <i>Sprint Retrospective</i>
    p.mt-5 Consiste en realizar un análisis de los requerimientos del sistema (Product Backlog) señalar cuáles serán los objetivos a corto o mediano plazo dentro de un sprint, es decir en la fase de desarrollo. Posteriormente los desarrolladores harán lo suyo, se realizan algunas pruebas y se retroalimenta de acuerdo con lo conseguido al terminar la última fase. 
    p.mt-4 Empresas tan importantes como Yahoo o Google implementan este tipo de metodología por su gran popularidad.
    .row.mt-5
      .col-10.offset-1
        .h4 Figura 2
        p Modelo ágil <i>Scrum</i>
        figure
          img(src="@/assets/template/tema-1-9.png", alt="texto que describa la imagen")
        .cajon.color-acento-botones.p-4.mt-5.bg-acento-botones-op50
          .row
            .col-2.d-none.d-lg-block
              figure
                img(src="@/assets/template/tema-1-10.svg", alt="Texto que describa la imagen")
            .col-12.col-lg-10
              .h4.mb-0 Test Driven Development (TDD)
              p #[strong Según Astel (2003) ] ”El Test Driven Development, es un tipo de desarrollo donde se mantiene un exhaustivo juego de pruebas del programador, su objetivo principal es que ninguna parte del código pase a producción sin realizar antes las pruebas asociadas y tener la aprobación”.
              p.mt-3 Se trata de un desarrollo orientado a las pruebas, donde cambia la mentalidad del equipo de desarrollo agilizando los resultados y aumentando la calidad del producto.
              p.mt-3 La tendencia actual es integrar TDD a cualquier metodología ya sea ágil (<i>Scrum</i> Alliance - TDD and Scrum, 2011) o tradicional (Letelier et al., s. f.), y aprovechar los beneficios de practicar una metodología que siempre permite deshacer los errores, asegurar una calidad del producto y protegerse de errores tanto malintencionados como humanos.
        .h4.mt-5 Figura 3
        p <i>Test Driven</i> (TDD)
        figure.mt-4
          img(src="@/assets/template/tema-1-11.png", alt="Texto que describa la imagen")
          figcaption.mt-3 Referencia Nota. https://bit.ly/3waI6hg
        .cajon.color-acento-botones.p-4.mt-5.bg-acento-botones-op50
          .row
            .col-2.d-none.d-lg-block
              figure
                img(src="@/assets/template/tema-1-12.svg", alt="Texto que describa la imagen")
            .col-12.col-lg-10
              .h4.mb-0 Mobile-D. Según Abrahamsson (2004):
              p Es una metodología de desarrollo especialmente diseñada para el desarrollo de aplicaciones móviles, que se basa en la integración de prácticas ágiles como <i>Extreme Programming y Cristal</i>. Presenta las siguientes características: es orientada a pruebas, la programación en parejas, la integración continua y refactorización, así como las tareas de mejoras del proceso del <i>software</i>.
    p.mt-5 La metodología contempla las fases de: exploración, inicialización, producción, estabilización y pruebas. Cada una posee un día de planificación y un día de entrega.
    .row.mt-4
      .col-10.offset-1
        .h4 Figura 4
        p Ciclo de desarrollo Mobile-D
    figure.mt-4
      img(src="@/assets/template/tema-1-13.svg", alt="Texto que describa la imagen")
      figcaption Referencia Nota. Escobar, 2014
    .row.mt-5
      .col-10.offset-1
        LineaTiempoD.color-primario
          .row(numero="1" titulo="Exploración")
            p.font-16 En esta fase se espera recolectar la información necesaria para la adecuada orientación del proyecto, sus requisitos, su alcance y las partes interesadas en el producto <i>(Stakeholder)</i>
          .row(numero="2" titulo="Inicialización")
            p.font-16 En esta fase se realiza la preparación de recursos físicos y tecnológicos como la formación del equipo del trabajo, los equipos tecnológicos de uso, etc.
          .row(numero="3" titulo="Producción")
            p.font-16 En esta fase se implementan las funcionalidades que requiere el producto utilizando un desarrollo iterativo, consta de 3 etapas:
            ul.lista-ul
              li 
                i.fas.fa-angle-right
                | Día de planificación, en donde se ejecutan los test de aceptación.
              li
                i.fas.fa-angle-right
                | Día de trabajo, correspondiente al desarrollo de funcionalidades y día de entrega.
              li
                i.fas.fa-angle-right
                | Día de entrega, cuando se realiza la entrega de funcionalidad.
          .row(numero="4" titulo="Estabilización")
            p.font-16 Es la fase donde se realiza la integración y se verifica el correcto funcionamiento del sistema y la calidad del <i>desarrollo</i>, también se realiza la documentación del proyecto. 
          .row(numero="5" titulo="Pruebas del sistema")
            p.font-16 En esta fase se realiza la verificación del funcionamiento de todos los requerimientos establecidos por el cliente y en el caso de encontrar errores se deben solucionar en esta fase.
    .row.mt-5
      .col-10.offset-1
        .tarjeta.color-primario.p-3.mb-5.bg-azul-degradado
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-2
              img(src="@/assets/template/tema-1-14.svg").w-75.margin-0-auto
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0.text-white
                  h2.mb-1 Metodología Mobile-D
                  p.font-16.p-0 A continuación, puede ampliar información sobre la metodología Mobile-D. Video sobre Metodologías de Desarrollo de Software Mobile-D
                .col-sm-auto
                  a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=I3yMHHgQCEk" target="_blank")
                    span.font-16 Enlace web
                    i.fas.fa-link




</template>

<script>
import Muestras from '../components/Muestras' // borrar una vez el componente "Muestras" no se necesite
export default {
  name: 'Tema1',
  components: {
    Muestras, // borrar una vez el componente "Muestras" no se necesite
  },
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
