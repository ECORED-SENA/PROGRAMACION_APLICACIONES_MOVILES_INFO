<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/fondo-banner-principal.png')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0 PROGRAMACIÓN DE APLICACIONES PARA DISPOSITIVOS MÓVILES
          
          .h2 Información del programa
          .banner-principal__datos
            ul
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Programación de aplicaciones para dispositivos móviles
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 228123
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Total Horas: 
                p.banner-principal__datos__item__texto 2256 horas
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Duración en meses: 
                p.banner-principal__datos__item__texto 15 meses
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto virtual
              //-- li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Requisito de ingreso: 
                .banner-principal__datos__item__texto
                  ul.lista-ul
                    li
                      i.lista-ul__vineta
                      p Solicitud de las Instituciones del Sistema General de Seguridad Social en Salud.
                    li
                      i.lista-ul__vineta
                      p Profesionales, tecnólogos y técnicos de salud que brindan atención a las víctimas de ataque con agentes químicos.
                    li
                      i.lista-ul__vineta
                      p Cumplir con el trámite de selección definido por el Centro de Formación.
                    li
                      i.lista-ul__vineta
                      p Se requiere que el aprendiz AVA (Ambientes Virtuales de Aprendizaje) tenga dominio de elementos básicos en el manejo de herramientas informáticas y de comunicación como correo electrónico, chat, procesadores de texto, software para presentaciones, navegadores de Internet, y otros sistemas y herramientas tecnológicas necesarias para la formación virtual.

        .d-none.d-lg-block.col-lg-5
          //- img(src="@/assets/curso/banner-princiapal.svg")
          .video.shadow-box
            | <iframe data-v-1f9e4816="" width="560" height="315" src="https://www.youtube.com/embed/hlH1xWz6Gyw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 1. Presentación
    p.mb-3  El programa técnico en programación de aplicaciones para dispositivos móviles busca formar talento humano con las competencias y las habilidades requeridas por la industria del desarrollo de <i>software</i> para dispositivos móviles.
    p.mb-3  La tecnología cambia día a día y evoluciona de manera exponencial con el camino que inició la llegada de los computadores y el progreso hacia los dispositivos móviles dando paso a la trasformación social y cultural de comercio, trabajo y entretenimiento por medio de estos dispositivos móviles inteligentes o en inglés Smartphone. Esta trasformación indica que en un corto lapso de tiempo toda la tecnología migrara y se transformara en un entorno móvil; razón fundamental para contar con herramientas de capacitación que permitan hacer parte la nueva transformación tecnológica no solo como espectadores sino como agentes activos del cambio y la evolución. 
    p.mb-3  Los colombianos no son productores de gran contenido de <i>hardware</i>, pero si cuenta con el capital humano que puede aportar grandes ideas de transformación tecnológica a través de la construcción de software para dispositivos móviles y este técnico proporciona herramientas básicas para entrar de manera firme al desarrollo de aplicaciones que busquen cerrar la brecha tecnológica en todos los ámbitos sociales especialmente en los ambientes empresariales de producción y comercialización.
    p.mb-3  A lo largo del programa y las actividades que se deben realizar, permiten conocer de forma clara las herramientas para tomar la mejor decisión y encontrar la resolución de problema tecnológicos con la capacidad de realizar una interfaz gráfica basada en el tipo de usuario, conectar la aplicación a una base de datos según el tipo de aplicación y generar las pruebas para el desarrollo de una aplicación que satisfaga las necesidades y que se elaboren productos de calidad para que se logre el despliegue del aplicativo en las tiendas de aplicaciones móviles como <i>AppStore</i> y <i>PlayStore</i>. 
    p.mb-3  El perfil de desarrollador de aplicaciones móviles le permite no solo ser un buen programador, sino que, también podrá participar en el análisis de problemas y la selección de las herramientas tecnológicas más óptimas para implementar soluciones rápidas y eficientes reduciendo los tiempos y costos. Este programa con seguridad le permitirá trabajar como desarrollador independiente <i>“FreeLancer”</i> o de manera colaborativa en grupos de trabajo multidisciplinar para el desarrollo de aplicaciones móviles que permitan una modernización digital y contribuir con el desarrollo económico, social y tecnológico del país. 

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 2. Justificación del programa
    p.mb-3 Como parte de las estrategias del Estado Colombiano para mantener y mejorar el desarrollo económico, el Estado promovió la Ley 1834 de 2017 – Ley Naranja, la cual tiene como objeto desarrollar, fomentar, incentivar y proteger las industrias creativas. Estas son entendidas como aquellas industrias que generan valor en razón de sus bienes y servicios, los cuales se fundamentan en la propiedad intelectual. Integra medios digitales, diseño y publicidad para el desarrollo de contenidos que impulsen el emprendimiento y enfoque de los sectores económicos a diversos mercados.
    p.mb-3  El desarrollo de soluciones para dispositivos móviles se convierte en una gran herramienta para impulsar la economía naranja y las industrias creativas, pues utiliza las plataformas tecnológicas para llegar de manera innovadora a nuevos mercados y apertura de fronteras. El desarrollo para dispositivos móviles, además, guarda estrecha relación con tecnologías emergentes como la realidad virtual, aumentada y mixta y se integra de forma eficiente con la computación en la nube y la visión artificial, eslabones propios de la cuarta revolución industrial.
    p.mb-3  Los dispositivos móviles se han convertido en elementos permanentes de uso personal y empresarial. Por tal motivo, las aplicaciones móviles ocupan un importante lugar entre las herramientas de comunicación rápidas y eficientes. El creciente uso de dispositivos inteligentes ha provocado que las llamadas App, se conviertan en estrategias digitales para potenciar el modelo de negocios, conexión con las personas, las empresas y los grupos de valor. El desarrollo móvil se aplica de gran manera como canal de comunicación para el despliegue de contenido, educación, finanzas, compras y entretenimiento, entre otras actividades. 
    p.mb-3  Además, se requiere de la formación integral de recurso humano que permita aprovechar las ventajas ofrecidas por la Industria 4.0, los ambientes de programación modernos y las capacidades ofrecidas por los dispositivos móviles, de tal forma que se logre un despliegue ágil de aplicaciones.
    p.mb-3  Es fundamental la formación de técnicos con habilidades y destrezas en el uso y aprovechamiento de los entornos de programación para soluciones móviles, que permitan implementar aplicaciones modernas que permitan aprovechar las arquitecturas, sensores y componentes de los dispositivos actuales.
    p.mb-3  Programas que permitan al aprendiz, adquirir habilidades y desarrollar competencias usando diversos métodos para programar aplicaciones móviles versátiles, reconocer la diferencia entre aplicaciones nativas e híbridas, ofrecer arquitecturas livianas, que interactúen con las funcionalidades de los dispositivos móviles, potenciando el alcance de las soluciones. Diseños curriculares modernos que incorporen el uso de patrones de diseño, librerías y herramientas que para construir soluciones móviles de calidad y el uso de frameworks o entornos de programación con alto grado de reconocimiento, para las distintas plataformas tecnológicas como IOS o Android.
    p.mb-3  Se requiere entonces, el desarrollo de competencias tendientes al aprovechamiento de recursos tecnológicos, incorporando módulos de formación relacionados con la comprensión de requisitos de software, implementación de bases de datos y codificación de software para la construcción de soluciones ejecutables en dispositivo móviles. La transformación digital, modernización en las entidades públicas y privadas, así como la necesidad creciente en la industria creativa y economía naranja, requieren de profesionales con habilidades y destrezas para la programación de software que aproveche al máximo los recursos y arquitecturas móviles.
    p.mb-3  Es fundamental de acuerdo con la Misión el SENA, apoyar en el cierre de brechas digitales del país, disminuyendo el déficit de profesionales en la programación de software para dispositivos móviles, así como promover el empresarismo y emprendimiento derivado de iniciativas en el aprovechamiento de las nuevas tecnologías.
    p.mb-3  El programa técnico en programación de aplicaciones para dispositivos móviles ofrece la oportunidad de incorporar personal con alta calidad humana, laboral y profesional en todos los sectores, ya sean industriales, comerciales, de servicios, extractivos o primarios, contribuyendo con el desarrollo económico, social y tecnológico del país. 
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 3. Competencias a desarrollar
    ul.lista-ul
      li  
        i.fas.fa-check  
        | Generar hábitos saludables de vida mediante la aplicación de programas de actividad física en los contextos productivos y sociales.
      li  
        i.fas.fa-check  
        | Interactuar en el contexto productivo y social de acuerdo con principios éticos para la construcción de una cultura de paz.
      li  
        i.fas.fa-check  
        | Razonar cuantitativamente frente a situaciones susceptibles de ser abordadas de manera matemática en contextos laborales, sociales y personales.
      li  
        i.fas.fa-check  
        | Desarrollar procesos de comunicación eficaces y efectivos, teniendo en cuenta situaciones de orden social, personal y productivo.
      li  
        i.fas.fa-check  
        | Gestionar procesos propios de la cultura emprendedora y empresarial de acuerdo con el perfil personal y los requerimientos productivo y social.
      li  
        i.fas.fa-check  
        | Aplicar prácticas de protección ambiental, seguridad y salud en el trabajo de acuerdo con las políticas organizacionales y la normatividad vigente.
      li  
        i.fas.fa-check  
        | Interactuar en lengua inglesa de forma oral y escrita dentro de contextos sociales y laborales según los criterios establecidos por el Marco Común Europeo de Referencia para las Lenguas.
      li  
        i.fas.fa-check  
        | Utilizar herramientas informáticas de acuerdo con las necesidades de manejo de información.
      li  
        i.fas.fa-check  
        | Ejercer derechos fundamentales del trabajo en el marco de la constitución política y los convenios internacionales.
      li  
        i.fas.fa-check  
        | Establecer requisitos de la solución de software de acuerdo con estándares y procedimiento técnico.
      li  
        i.fas.fa-check  
        | Desarrollar la solución de software de acuerdo con el diseño y metodologías de desarrollo.
      li  
        i.fas.fa-check  
        | Administrar base de datos de acuerdo con los estándares y requisitos técnicos.
      li  
        i.fas.fa-check  
        | Aplicar el enfoque de la Programación Orientada a Objetos.
      li  
        i.fas.fa-check  
        | Construir sitios web según técnicas de interoperabilidad y protocolos técnicos.
      li  
        i.fas.fa-check  
        | Diseñar aplicaciones móviles de acuerdo con patrones y procedimientos técnicos.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 4. Perfil de ingreso
    ul.lista-ul
      li  
        p Nivel académico adecuado para caracterizar al aspirante de acuerdo con el perfil de egreso: <b>básica</b>
      li  
        p Secundaria Grado: <b>9°</b>
      li  
        p Requiere certificación académica: <b>sí</b>
      li  
        p Requiere formación para el trabajo y desarrollo humano:  <b>no</b>
      li  
        p Edad mínima definida en la ley: <b>14 años</b>
      li  
        p Requisitos adicionales: <b>superar prueba de aptitud y conocimiento</b>

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 5. Perfil de egreso
    p.mb-3  El egresado del programa técnico programación de aplicaciones para dispositivos móviles, es un talento humano con una formación profesional integral que estará en la capacidad de codificar software para dispositivos móviles, desarrollar aplicaciones, diseñar y generar bases de datos para dispositivos móviles, crear Interfaces para aplicaciones móviles, interpretar diagramas para la codificación, realizar pruebas de funcionamiento y brindar soporte al software; con gran capacidad para trabajar en equipo, seguir orientaciones, y capacidad de adaptación al cambio.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 6. Estrategia metodológica
    p.mb-4  Centrada en la construcción de autonomía para garantizar la calidad de la formación en el marco de la formación por competencias, el aprendizaje por proyectos y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales; soportadas en la utilización de las tecnologías de la información y la comunicación, integradas, en ambientes virtuales de aprendizaje, que en todo caso recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias.
    p.mb-4  Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el que hacer y los resultados de aprendizaje que logra a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:
    ul
      li  El instructor - Tutor  
      li  El entorno
      li  Las TIC
      li  El trabajo colaborativo
 



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
