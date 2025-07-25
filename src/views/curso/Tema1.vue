<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'1. Impacto ético de la tecnología en el ámbito laboral y social     '")
  .container.tarjeta.tarjeta--blanca.px-4.pt-4.px-md-5.pt-md-5.overflow-hidden
    p.mb-4 A lo largo de la evolución de las sociedades, el trabajo ha sido un pilar fundamental en la configuración de las relaciones sociales y en el desarrollo de capacidades individuales y colectivas. Más allá de su función económica, el trabajo es una expresión de dignidad humana y un espacio donde se reflejan los valores y derechos de una sociedad. Sin embargo, en el contexto de la globalización, los modelos productivos han introducido dinámicas complejas que afectan directamente estos valores fundamentales, poniendo a prueba los principios éticos que regulan el ámbito laboral y su impacto en el tejido social. La búsqueda de eficiencia y competitividad, ha generado prácticas que desafían el respeto por los derechos laborales y la cohesión social, requiriendo una reflexión ética profunda sobre las implicaciones de estos cambios.
    .row.justify-content-center.mb-5
      .col-lg-7.mb-lg-0.mb-3
        .p-4.mb-4(style="background-color: #eaf8fd ")
          p.mb-0 A medida que los mercados y las empresas trascienden fronteras, el entorno laboral se ve influenciado por una globalización que introduce nuevos dilemas éticos y tecnológicos; ejemplo de esto son las prácticas como la explotación laboral de trabajadores y el desplazamiento laboral por la tecnología, planteando interrogantes sobre la equidad, la seguridad laboral y el respeto a los derechos humanos, en diferentes contextos culturales y normativos. 
        p.mb-4 Estos dilemas éticos en el entorno laboral globalizado, exigen un análisis profundo de las implicaciones de tales prácticas, evaluando hasta qué punto el compromiso con los derechos laborales, se mantiene frente a las presiones económicas y los cambios tecnológicos que surgen.
          br
          br
          |Para abordar estos desafíos, es necesario profundizar las temáticas que se estudiarán a continuación.
      .col-lg-5.col-7: img(src='@/assets/curso/temas/3.png', alt='')
    .bg-full-width.bg-color-2(style="background-color: #f0e9f6")
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-5.col-7.mb-lg-0.mb-3
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/temas/4.png', alt='')
          .col-lg-7
            h2.mb-4(data-aos="flip-up") Dilemas éticos
            p.mb-4(data-aos="fade-right") En un mundo cada vez más interconectado, los avances tecnológicos y la globalización han redefinido las dinámicas laborales, introduciendo desafíos éticos significativos que requieren atención urgente. Desde el impacto de la automatización y la digitalización en la estabilidad laboral hasta las brechas de desigualdad generadas por la economía digital, los dilemas éticos se presentan como una constante que exige un análisis profundo y comprometido. En este contexto, el estudio de temas como la transformación tecnológica, la automatización y la inclusión digital se vuelve esencial para entender las implicaciones sociales y éticas que estos fenómenos traen consigo, así como para diseñar respuestas que promuevan una transición laboral inclusiva y equitativa. A continuación, el PDF Dilemas éticos, explora estas temáticas, ofreciendo un enfoque crítico sobre la necesidad de armonizar el progreso tecnológico con la protección de los derechos laborales y la dignidad humana.

            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/anexo1.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Dilemas éticos.


    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            // Referencias agregadas según formato solicitado
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/51423" target="_blank" rel="noopener noreferrer") García Peregrín, E. (2018). Bioética: temas para el debate. Vol. 2: ( ed.). Bubok Publishing S.L.
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/41139" target="_blank" rel="noopener noreferrer") Garza Grimaldo, J. G. & Valqui Cachi, C. (2017). Los valores en la dialéctica de la humanidad y la naturaleza en el siglo XXI: ( ed.). Ediciones y Gráficos Eón.
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/40950" target="_blank" rel="noopener noreferrer") Núñez de Castro, I. (2017). La bioética: un camino para el presente: ( ed.). ITESO - Instituto Tecnológico y de Estudios Superiores de Occidente.
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/219184" target="_blank" rel="noopener noreferrer") Pinilla Forero, J. (2022). Ética y bioética en la práctica profesional. Revista Colombiana de Ciencias Administrativas, 4 (1), 78-93: ( ed.). Fundación Universitaria San Mateo.
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://repositorio.cepal.org/server/api/core/bitstreams/3807d08e-c4b5-41de-9fe5-ad115f2f1447/content" target="_blank" rel="noopener noreferrer") M. E. Valenzuela, M. L. Scuro e I.Vaca Trigo,“Desigualdad, crisis de los cuidados y migración del trabajo doméstico remunerado en América Latina”, serie Asuntos de Género, N° 158 (LC/TS.2020/179), Santiago, Comisión Económica para América Latina y el Caribe (CEPAL), 2020
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://ejcls.adapt.it/index.php/rlde_adapt/article/view/452" target="_blank" rel="noopener noreferrer") Spemolla, G. C. (2017). El trabajo en la era digital: Reflexiones sobre el impacto de la digitalización en el trabajo, la regulación laboral y las relaciones laborales. Relaciones Laborales y Derecho del Empleo.
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.revistasice.com/index.php/BICE/article/download/3598/3598" target="_blank" rel="noopener noreferrer") de la Cuesta González, M. (2004). El porqué de la responsabilidad social corporativa. 45–58.
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://youtu.be/pE3VeNcYZ64" target="_blank" rel="noopener noreferrer") Banco Interamericano de Desarrollo (BID). (2020, 15 de septiembre). La crisis de la desigualdad | Lanzamiento del informe [Video]. YouTube.
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://youtu.be/F0r9hl9kYhU" target="_blank" rel="noopener noreferrer") Universidad Técnica Particular de Loja (UTPL). (2013, 16 de octubre). Normas de la RSE [Responsabilidad Social Empresarial] [Video]. YouTube.


         

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')
      
</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({}),

  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass">
.tabs-content
  background-color: $color-sistema-h
.img-infografica
  background-color: $color-adicional-1

.SplitContainer
  background: rgb(85,122,250)
  background: linear-gradient(0deg, rgba(232,238,253,1) 0%, rgba(232,238,253,1) 50%, rgba(255,255,255,1) 50%)

  .yellowCard
    padding: 2rem
    background-color: #FBF6DB

.PurpleContainer
  background-color: rgb(255,253,246)

.SplitContainer2
  background: rgb(85,122,250)
  background: linear-gradient(0deg, rgba(255,255,255,1) 0%, rgba(255,255,255,1) 50%, rgba(255,253,246,1) 50%)

  .yellowCard
    padding: 2rem
    background-color: #FBF6DB
</style>
