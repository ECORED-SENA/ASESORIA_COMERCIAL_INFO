<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/fondo-banner-principal.svg')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0 Asesoría comercial
          
          .h2 Información del programa
          .banner-principal__datos
            ul
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Asesoría comercial
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 631101
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Total Horas: 
                p.banner-principal__datos__item__texto 2208
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Duración: 
                p.banner-principal__datos__item__texto 15 meses
              li.mb-0.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto virtual            

        .d-none.d-lg-block.col-lg-5
          //- img(src="@/assets/curso/banner-princiapal.svg")
          .video
            | <iframe data-v-1f9e4816="" width="560" height="315" src="https://www.youtube.com/embed/kBcHYCTVJTE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 1. Presentación

    p Bienvenido, estimado aprendiz:

    p El Servicio Nacional de Aprendizaje - SENA le da una cordial bienvenida al desarrollo del programa de formación Asesoría comercial de nivel Técnico laboral.

    p Este programa está asociado a la ocupación de vendedores de ventas no técnicas, sobre la cual existen diversas denominaciones en las que es posible desempeñarse, tales como vendedor tienda a tienda, vendedor externo, vendedor viajero, vendedor de servicios financieros, representante de ventas, promotor de venta, entre otros.

    p Durante el proceso formativo, tendrá la oportunidad de desarrollar habilidades en prospectar clientes, vender bienes y servicios, y monitorear la satisfacción y demás requerimientos del cliente. Para ello, tendrá a disposición un equipo de instructores con perfil idóneo para entregarle todas las orientaciones posibles, que le permitan el logro de los resultados de aprendizaje específicos, claves y transversales; además, podrá acompañar su proceso con el trabajo colaborativo, el uso de herramientas tecnológicas y el entorno que le rodea.

    p Una vez egresado, contará con las herramientas mínimas para ingresar al aparato productivo, poner a prueba sus conocimientos en la vida laboral, y así iniciar una carrera profesional en el mundo del comercio y de las ventas. Adicionalmente, contará con una plataforma académica que le permitirá llevar a cabo un proceso de articulación con otros niveles de formación, como el tecnológico, el de especialización tecnológica y el profesional.

    p Una vez egresado, contará con las herramientas mínimas para ingresar al aparato productivo, poner a prueba sus conocimientos en la vida laboral, y así iniciar una carrera profesional en el mundo del comercio y de las ventas. Adicionalmente, contará con una plataforma académica que le permitirá llevar a cabo un proceso de articulación con otros niveles de formación, como el tecnológico, el de especialización tecnológica y el profesional.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 2. Justificación<br>del programa

    p Actualmente, el aumento cada vez más acelerado de la renta y servicios finales producidos por la economía y la dotación de recursos técnicos de la producción mundial ha generado una serie de cambios respecto a la comercialización de productos y servicios; y sin duda alguna, conceptos como globalización, competitividad, hiperconectividad, diferenciación, etc., han originado la producción a gran escala, representando un abatimiento en los costos para las mipymes (Llamas, 2004).

    p Es por ello que, para que la entrega de productos y servicios al consumidor final sea efectiva, se hace necesario contar con un equipo de asesores comerciales conocedores y dominadores de cada uno de los pasos de la ciencia mercadológica de la distribución (Llamas, 2004). Para satisfacer esta necesidad, el SENA oferta el programa Técnico en asesoría comercial, con el que fortalecerá al vendedor empírico y lo ayudará a convertirse en un asesor comercial con conocimientos técnicos y valores éticos, necesarios para impulsar el comercio al por menor del país.

    p Con lo anterior, se constata que, al contratar las empresas personal competente en el arte de vender, se obtiene una doble ganancia, ya que cuando el vendedor se actualiza en métodos y racionaliza actitudes que provocan la fidelización de clientes en las organizaciones, la producción aumenta sensible y rápidamente, produciendo una integración ética y profesional.


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 3. Competencias<br> para desarrollar

    h5 Competencias técnicas:

    ul.lista-ul.mb-4
      li
        i.fas.fa-angle-right
        p.mb-0 #[strong 260101033] - Prospectar clientes de acuerdo con los segmentos objetivo y estrategia de ventas.
      li
        i.fas.fa-angle-right
        p.mb-0 #[strong 260101047] - Vender productos y servicios de acuerdo con las necesidades del cliente y objetivos comerciales.
      li
        i.fas.fa-angle-right
        p.mb-0 #[strong 260101034] - Monitorear al cliente de acuerdo con metodologías de evaluación y seguimiento.
    
    h5 Competencias claves:

    ul.lista-ul.mb-4
      li
        i.fas.fa-angle-right
        p.mb-0 #[strong 240201528] - Razonar cuantitativamente frente a situaciones susceptibles de ser abordadas de manera matemática en contextos laborales, sociales y personales.
      li
        i.fas.fa-angle-right
        p.mb-0 #[strong 220501046]  - Utilizar herramientas informáticas de acuerdo con las necesidades de manejo de información.
      li
        i.fas.fa-angle-right
        p.mb-0 #[strong 240202521]- Interactuar en lengua inglesa de forma oral y escrita dentro de contextos sociales y laborales, según los criterios establecidos por el Marco Común Europeo de Referencia para las Lenguas.
      li
        i.fas.fa-angle-right
        p.mb-0 #[strong 240201524] - Desarrollar procesos de comunicación eficaces y efectivos, teniendo en cuenta situaciones de orden social, personal y productivo.
      li
        i.fas.fa-angle-right
        p.mb-0 #[strong 220201501] - Aplicación de conocimientos de las ciencias naturales de acuerdo con situaciones del contexto productivo y social.
    
    h5 Competencias transversales:

    ul.lista-ul.mb-4
      li
        i.fas.fa-angle-right
        p.mb-0 #[strong 240201530] - Resultado de aprendizaje de la inducción.
      li
        i.fas.fa-angle-right
        p.mb-0 #[strong 220601501] - Aplicar prácticas de protección ambiental, seguridad y salud en el trabajo, de acuerdo con las políticas organizacionales y la normatividad vigente.
      li
        i.fas.fa-angle-right
        p.mb-0 #[strong 210601501] - Ejercer derechos fundamentales del trabajo en el marco de la constitución política y los convenios internacionales.
      li
        i.fas.fa-angle-right
        p.mb-0 #[strong 240201526] - Enrique Low Murtra-Interactuar en el contexto productivo y social de acuerdo con principios éticos para la construcción de una cultura de paz.
      li
        i.fas.fa-angle-right
        p.mb-0 #[strong 230101507] - Generar hábitos saludables de vida mediante la aplicación de programas de actividad física en los contextos productivos y sociales.
      li
        i.fas.fa-angle-right
        p.mb-0 #[strong 240201529] - Gestionar procesos propios de la cultura emprendedora y empresarial de acuerdo con el perfil personal y los requerimientos de los contextos productivo y social.


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 4. Perfil<br> de ingreso

    p El nivel académico adecuado para caracterizar al aspirante de acuerdo con el perfil de egreso es básica secundaria, específicamente, de grado noveno (9°), con su respectiva certificación académica. No se requiere certificación de formación para el trabajo y desarrollo humano adicional. La edad mínima es de 14 años y los demás requisitos serán los que cada centro de formación solicite.
  
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 5. Perfil<br> de ingreso

    p Los titulados del programa Técnico en asesoría comercial están cualificados para negociar técnicamente productos y servicios, prospectar, corroborar las experiencias de postventa a clientes y representar cualquier tipo de empresa en su área comercial. Para el desarrollo de estas labores, es necesario que los aprendices y titulados desarrollen habilidades blandas, como la responsabilidad, el trabajo en equipo, la proactividad, la honestidad con la empresa y sus prospectos.
  
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 6. Estrategia <br>metodológica

    p Centrada en la construcción de autonomía para garantizar la calidad de la formación en el marco de la formación por competencias, el aprendizaje por proyectos y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales; soportada en la utilización de las tecnologías de la información y la comunicación, integradas en ambientes virtuales de aprendizaje, que en todo caso recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias. 

    p Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el quehacer y los resultados de aprendizaje que logra a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:

    .row.g-4.justify-content-center.mb-0
      .col-5.col-sm-3.col-md-2
        figure.mb-2
          img.w-75.mx-auto(src='@/assets/curso/01.svg', alt='El instructor - tutor')
        p.text-center.mb-0
          strong El instructor - tutor
      .col-5.col-sm-3.col-md-2
        figure.mb-2
          img.w-75.mx-auto(src='@/assets/curso/02.svg', alt='El instructor - tutor')
        p.text-center.mb-0
          strong El entorno
      .col-5.col-sm-3.col-md-2
        figure.mb-2
          img.w-75.mx-auto(src='@/assets/curso/03.svg', alt='El instructor - tutor')
        p.text-center.mb-0
          strong Las TIC
      .col-5.col-sm-3.col-md-2
        figure.mb-2
          img.w-75.mx-auto(src='@/assets/curso/04.svg', alt='El instructor - tutor')
        p.text-center.mb-0
          strong El trabajo colaborativo

  //- Créditos
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 Créditos

    
    .creditos
      div(
        v-for="(creditoKey, index) of Object.keys(creditosData)"
        :class="index != Object.keys(creditosData).length -1 ? 'mb-4' : ''" 
      )
        .creditos__titulo {{configTitulos[creditoKey]}}
        table
          tbody
            tr(
              v-for="(item, idx) of creditosData[creditoKey]" 
              :key="creditoKey+idx"
            )
              td.text-bold(colspan='2' v-html="renderText(item.nombre)")
              td(colspan='2' v-html="renderText(item.cargo)")
              td(colspan='3' v-html="renderText(item.centro)")

  Footer

</template>
<script>
export default {
  name: 'Inicio',
  data: () => ({
    configTitulos: {
      liderEquipo: 'ECOSISTEMA DE RECURSOS EDUCATIVOS DIGITALES',
      contenidoInstruccional: 'CONTENIDO INSTRUCCIONAL',
      desarrolloProducto:
        'DISEÑO Y DESARROLLO DE RECURSOS EDUCATIVOS DIGITALES',
      gestoresRepositorio: 'GESTORES DE REPOSITORIO',
    },
  }),
  computed: {
    creditosData() {
      return this.$config.creditos
    },
  },
  methods: {
    renderText(textObj) {
      let newText = ''
      if (Array.isArray(textObj)) {
        textObj.forEach((texto, index) => {
          newText += (index ? '<br/>' : '') + texto
        })
      } else {
        newText += textObj
      }
      return newText
    },
  },
}
</script>

<style lang="sass">
.creditos
  td, th
    border-color: $color-sistema-c
</style>
