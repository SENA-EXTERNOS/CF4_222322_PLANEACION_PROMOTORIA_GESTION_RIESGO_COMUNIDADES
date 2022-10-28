<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .row.mb-5
      .col-md-9.mb-4.mb-md-0
        p Estimado aprendiz, en este componente formativo se evidencia como la participación ciudadana es de vital importancia en la sociedad para los procesos de creación y promoción de los planes de gestión del riesgo de desastres, ya que son las personas los actores centrales y principales dentro de los escenarios de riesgo, y por ende deben capacitarse y así actuar de manera adecuada, para asegurar una correcta prevención y respuesta a las actividades que puedan afectar la salud humana, el entorno y los bienes de las comunidades. 
 
        p Las temáticas que se trabajarán a continuación, permitirán profundizar tópicos que van desde los grupos focales, hasta los mecanismos de participación constitucionales, desde la clasificación de las comunidades, hasta las técnicas educativas. Por favor, explore con atención el siguiente video que le mostrará la importancia de trabajar por el bienestar común de las comunidades.

      .col-lg-3
        img.img-a(src='@/assets/curso/temas/tema_1/img_1.png', alt='Texto que describa la imagen')


    figure.mb-5(data-aos="zoom-in-down")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video: Leyenda del video
    
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
