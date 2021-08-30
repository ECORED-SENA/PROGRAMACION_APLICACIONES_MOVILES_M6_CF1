<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    figure.mt-4
      img(src="@/assets/template/tema-0-1.png", alt="Texto que describa la imagen")
    .row.mt-5
      .col-12.col-lg-8
        p Sin duda los dispositivos móviles hacen parte de nuestro día a día y cada vez son más avanzados. La creciente demanda de <i>software</i> específico para estos dispositivos ha generado nuevos desafíos para los desarrolladores, ya que este tipo de aplicaciones tienen características propias, restricciones y necesidades únicas.
        p.mt-3 Por esta razón es importante definir cuáles serán las tecnologías más adecuadas para la programación de móviles, y una de las arquitecturas más implantadas es la proporcionada por el sistema <i>Android</i>. En los dispositivos móviles actuales pueden utilizarse tres tipos de aplicaciones diferentes: nativas, híbridas y <i>web</i>. En este componente se tratarán las aplicaciones móviles nativas.
        p.mt-3 Las aplicaciones nativas, son aquellas que enfocan su desarrollo para una plataforma específica como <i>Android, IOS, y Windows</i>, haciendo uso de su correspondiente lenguaje de programación, el cual permite tener compatibilidad con sus características, que para el caso de <i>Android</i>, usa los lenguajes como <i>Java, Kotlin, Objetive-C</i> o <i>Switf</i>  para la plataforma <i>IOS</i>, y el lenguaje <i>C++</i> o <i>C#</i> para la plataforma <i>Windows</i>.
        p.mt-3 Las aplicaciones nativas son las más eficientes, y pueden salir a producción en las tiendas más populares como son <i>AppStore, Google Play, AppGallery</i> entre otras; una de sus características principales es que permiten enviar notificaciones para hacer promociones comerciales de negocios, productos, etc., en cuanto al tiempo de desarrollo es mucho más largo y por tanto son más costosas debido a la especialidad que deben tener los programadores en cada lenguaje. Su uso se encuentra en aplicaciones complejas como editores de video, aplicaciones de medicina, aplicaciones de ingeniería etc.
        p.mt-3 Desde el punto de vista de los programadores uno de los mayores inconvenientes presentados, es que para que una misma aplicación pueda utilizarse en dos o más plataformas distintas, hay que desarrollar la misma aplicación en los diferentes lenguajes, iniciando desde cero y, necesitando más tiempo de desarrollo y más costo.  
      .col-4.offset-4.offset-lg-0
        figure
          img(src="@/assets/template/tema-0-2.svg", alt="Texto que describa la imagen")

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
