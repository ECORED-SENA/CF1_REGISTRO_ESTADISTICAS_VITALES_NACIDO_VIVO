<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="fade-right")
      .titulo-principal__numero.text-white
        span
          i.fas.fa-info
      h1 Introducción

    p Bienvenido a este componente formativo denominado “Lineamientos de los Subsistemas de registro civil y de estadísticas vitales.”, el cual tiene como fin dar a conocer los elementos, normativas y técnicas que están relacionadas con el registro de estadísticas vitales y nacido vivo.
    p.mb-5 Para comenzar el recorrido por el mismo, visite el recurso didáctico que se propone a continuación:
    
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
