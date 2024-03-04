<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Aplicaciones para programar dispositivos IoT

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-8.order-lg-1.order-2(data-aos="fade-right")
        p Para programar en IoT se puede realizar en Java, lenguaje C, Python, JavaScript son algunos de los lenguajes más importantes que se utilizan en el desarrollo de IoT
        .BGR07.p-3
          .row.justify-content-around.align-items-center
            .col-lg-2.col-sm-3.col-4
              img(src="@/assets/curso/temas/tema3/code.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p Los dispositivos IoT cuentan con sensores que registran y transforman lo físico o químico en datos electrónicos que podemos manejar.
            p Cualquier dispositivo IoT permite conectarse a otros dispositivos y aplicaciones IoT para transmitir información utilizando protocolos estándar de Internet, veamos los siguientes:
      .col-lg-4.col-8.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
        img(src="@/assets/curso/temas/tema3/img302.png")
  
    .row.justify-content-center.align-items-start.mb-5
      .col-lg-10
        img.img-a.img-t.mb-5(data-aos="zoom-in")(src='@/assets/curso/temas/tema3/img33.png', alt='')

    #t_3_1.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 3.1 Entornos de desarrollo y Frameworks
    
    .bloque-texto-g.bloque-texto-g--inverso.color-secundario.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema3/img.3.1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Un entorno de desarrollo o IDE es un software que combina en un solo lugar todas las herramientas para poder desarrollar un proyecto de software, la combinación de varios procesos de programación, cuentan con un editor, compilador, un desbloqueador de las gestiones de código genérico, las mismas se dan en entornos de los lenguajes de desarrollo Python y Java, los sistémicos y programadores pueden testear por medio de estos entornos de desarrollo los diferentes segmentos de código, esto para poder identificar cualquier error de la aplicación antes de salir al mercado. 
    br
    br
    p Los frameworks pueden ser una de las herramientas más importantes para los programadores en general. Se trata de toda una base de datos en las que se establecen proyectos completos, y que pueden ser utilizados las veces necesarias. 

    Separador    
    #t_3_2.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 3.2 Estándares de codificación y plantillas 
    p(data-aos="fade-down").mb-5 Los estándares de codificación concentran elementos de ingeniería sólidos para la programación en sus diferentes lenguajes y constituyen la base de cualquier orientación preventiva.<br><br>Los estandares de calidad más relevantes en la construcción de software, de acuerdo con las normas ISO, son los siguientes
    .col-lg-12.my-3
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/tema3/img3.2.png', alt='')
    <br><br>
    p Las herramientas de integración aprueban a las organizaciones a conseguir una mayor eficiencia, productividad y agilidad ya que integra diferentes aplicaciones de software y servicios, interfaces de programación de aplicaciones (API) datos y dispositivos para automatizar los procesos empresariales y ofrecer al usuario.<br><br>Las herramientas de gestión de cambios son cualquier cosa que se pueda utilizar para aliviar las tensiones que surgen durante un cambio en el proceso, el personal o el software.

    .row.justify-content-center(data-aos="fade-right")
      .col-lg-4.col-12.d-flex
        .tarjeta--boton.color-primario.p-4(style="background-color: #FED9D3; border-radius: 20px; padding: 100px")
          .row.justify-content-center.mb-3
            .col-6
              figure
                img(src='@/assets/curso/temas/tema3/Azure.svg',)

          h3.text-center Azure Pipelines
          p.text-small Son servicios en la nube que combina y realiza entrega continua, donde compila y prueba automáticamente el código para finalmente colocar el mismo a disposición de otros usuarios.
  
      .col-lg-4.col-12.d-flex
        .tarjeta--boton.color-primario.p-4(style="background-color: #FED9D3; border-radius: 20px; padding: 100px")
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/tema3/img001.svg',)

          h3.text-center Jenkins
          p.text-small  Es una herramienta de integración continua, siendo la misma de código abierto y se puede configurar en entornos productivos.

      .col-lg-4.mb-4.mb-lg-0
        .tarjeta--boton.color-primario.p-4(style="background-color: #FED9D3; border-radius: 20px; padding: 100px")
          .row.justify-content-center.mb-3
            .col-9
              figure
                img(src='@/assets/curso/temas/tema3/Gitlab.svg',)

          h3.text-center Gitlab
          p.text-small  Tiene un servicio en el cual se construye y prueba el software cada vez que el programador actualiza el repositorio.


    Separador    
    #t_3_3.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 3.3 Implementación de IoT
    .row.justify-content-center.align-items-start.mb-4
      .col-lg-5.col-8.mb-4.mb-lg-0
        img.img-a.img-t.mb-5(data-aos="zoom-in")(src='@/assets/curso/temas/tema3/img3.3.png', alt='')
      .col-lg-7.mb-4.mb-md-0(data-aos="fade-left")
        p(data-aos="fade-down").mb-5 Cuando miramos las implementaciones de proyectos en IoT pensamos que el conocimiento de inteligencia empresarial no deja de transformarse y, uno de los últimos negocios relevantes se debe a las aplicaciones IoT.<br><br>Se denomina aplicaciones IoT a las soluciones de software diseñadas para realizar tareas, en este caso, en base a la información procedente de dispositivos conectados a una red. Según datos de IDC, para el 2020, la cantidad de objetos conectados habrá alcanzado los 30 miles de millones, ofreciendo una oportunidad de ingresos de 1.7 miles de millones de dólares americanos, para el año 2030 la proyección sería de 125 mil millones conectados.<br><br>En la implementación de proyectos IoT se puede conectar hoy en dia cualquier objeto como:  
      .col-lg-9.my-3
          ul.lista-ul
            li
              i.fas.fa-angle-right.vcolor
              span Tráfico: como proyectos en Vehículos, Semáforos.
            li
              i.fas.fa-angle-right.vcolor
              span Objetos personales: Ropa, zapatos.
            li
              i.fas.fa-angle-right.vcolor
              span Hogar: Timbre, Garaje, Puertas hogar, Electrodomésticos 
            li
              i.fas.fa-angle-right.vcolor
              span Equipos electrónicos: todos.
            li
              i.fas.fa-angle-right.vcolor
              span Dispositivos de salud en control.
            li
              i.fas.fa-angle-right.vcolor
              pan Dispositivos de deporte.
          p(data-aos="fade-down").mb-5 Dentro del metaverso y comercio electrónico los proyectos de IoT serían fundamentales proyectos de esta línea para los diferentes almacenes o empresas en mejoramiento de los procesos de ventas y afinidad con sus clientes. 
    
          .mb-4.d-flex
      .d-flex.flex-wrap.align-items-center.pe-4(style="background-color: #083142; border-radius: 25px; padding: 10px")
          img.col-lg.d-none.d-lg-flex(src='@/assets/curso/temas/tema3/esquina.svg' style="max-width: 70px; left: 16px; position: absolute" data-aos="fade-left")
          h3.col.px-4.mb-0.text-white(data-aos="fade-right") Pruebas de conectividad

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-8.order-lg-1.order-2(data-aos="fade-right")
        p Cuando hablamos sobre las pruebas de conectividad las mismas se miden mediante herramientas de diagnóstico en el cual podemos verificar la conectividad entre los puntos de la red. Podemos realizar un análisis de la configuración y poder analizar datos del plano en vivo, las mismas pruebas de conectividad se usan para ayudar a controlar problemas de conexión de red como: 
        ol.lista-ol--cuadro
          li.d-flex 
            .lista-ol--cuadro__vineta(styte="color: #000")
              span a
            p.mb-0 Opciones incoherentes no deseadas.
          li.d-flex 
            .lista-ol--cuadro__vineta(styte="color: #000")
              span b
            p.mb-0 Opción obsoletas en la configuración esto se puede dar según las migraciones o cambios que tenga la arquitectura de hardware. 
          li.d-flex 
            .lista-ol--cuadro__vineta(styte="color: #FF6148")
              span c
            p.mb-0 Error en la variedad de servicio y funciones de la red.
        
      .col-lg-4.col-8.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
        img(src="@/assets/curso/temas/tema3/continuidad.svg")
        .mb-4.d-flex
      
    .d-flex.flex-wrap.align-items-center.pe-4(style="background-color: #083142; border-radius: 25px; padding: 10px")
      img.col-lg.d-none.d-lg-flex(src='@/assets/curso/temas/tema3/esquina.svg' style="max-width: 70px; left: 16px; position: absolute" data-aos="fade-left")
      h3.col.px-4.mb-0.text-white(data-aos="fade-right") Pruebas de funcionamiento
    .bloque1.p-0.mb-5
      .bloque-texto-b.color-secundario.p-4.mb-0(data-aos="fade-left")
        .bloque-texto-b__texto
    .row.justify-content-center.align-items-center.d-flex
      .col-lg-10.col-12
        p.mb-lg-0.mb-3 Dentro de las pruebas de funcionamiento se puede realizar el test de conectividad (Ver gráfico 4) mediante el valor de shapley ya que es un método de optimización de recursos y podemos aplicarlo a la conectividad o transmisión de paquetes, también mediante el ping podemos tomar los valores de conectividad de red. 
      .col-lg-2.col-8.px-5
        img.mb-0(alt="" src="@/assets/curso/temas/tema3/pruebafun.svg")   

    .row.justify-content-center.align-items-start.mb-5
      .col-lg-8
        img.img-a.img-t.mb-1(data-aos="zoom-in")(src='@/assets/curso/temas/tema3/ping.svg', alt='')
        .row.justify-content-center.align-items-center
    p Gráfico 4.  Testeo ping con una página web 
    p Pero se toma las direcciones IP de cabecera de red y se procede a llenar la tabla 2.    
    
    .row.justify-content-center.mb-4
    .col-lg-5
        .titulo-sexto.color-acento-contenido.mb-4(data-aos="fade-right")
          h5 Tabla 2
          span  Plantilla de seguimiento de conexiones punto a punto
        
        .tabla-a.color-acento-contenido(data-aos="zoom-in")
          table
            thead(style="border-color: transparent")
              tr
                th(style="background-color: #FED9D3;").text-center Nodo 
                th(style="background-color: #FED9D3;").text-center Valores de RED tiempo 
                th(style="background-color: #FED9D3;").text-center Excelente 
                th(style="background-color: #FED9D3;").text-center Regular 
                th(style="background-color: #FED9D3;").text-center Malo         
            tbody    
              tr
                th(style="background-color: #FFF;").text-center 1
                td(style="background-color: #FFF;").text-center 
                td(style="background-color: #FFF;").text-center
                td(style="background-color: #FFF;").text-center 
                td(style="background-color: #FFF;").text-center 
              tr
                th(style="background-color: #FAF0EF;").text-center 2
                td(style="background-color: #FAF0EF;").text-center 
                td(style="background-color: #FAF0EF;").text-center 
                td(style="background-color: #FAF0EF;").text-center 
                td(style="background-color: #FAF0EF;").text-center
              tr
                th(style="background-color: #FFF;").text-center 3
                td(style="background-color: #FFF;").text-center 
                td(style="background-color: #FFF;").text-center 
                td(style="background-color: #FFF;").text-center 
                td(style="background-color: #FFF;").text-center 
              tr
                th(style="background-color: #FAF0EF;").text-center 4
                td(style="background-color: #FAF0EF;").text-center 
                td(style="background-color: #FAF0EF;").text-center 
                td(style="background-color: #FAF0EF;").text-center 
                td(style="background-color: #FAF0EF;").text-center
              tr
                th(style="background-color: #FFF;").text-center 5
                td(style="background-color: #FFF;").text-center 
                td(style="background-color: #FFF;").text-center 
                td(style="background-color: #FFF;").text-center 
                td(style="background-color: #FFF;").text-center 

              
    .row
      .col-lg-4
        .cajon.color-secundario.p-4
          p En el anterior escenario podemos decir que tenemos N =5 donde sería los nodos que conforman la Red Power Line Communications (PLC), dando valores de red solicitados q que se pueden extraer los valores de red tiempo por puntos y realizar la comparación entre nodos dando rangos según la topología de red. 
          p Ejemplo: Excelente rango de 1 - 20 MS 
          p Regular sería de 1 - 30 MS 
          p Malo sería rango de 1 - 40 Ms pero con interrupciones y fallas 
          
      
    .d-flex.flex-wrap.align-items-center.pe-4(style="background-color: #083142; border-radius: 25px; padding: 10px")
      img.col-lg.d-none.d-lg-flex(src='@/assets/curso/temas/tema3/esquina.svg' style="max-width: 70px; left: 16px; position: absolute" data-aos="fade-left")
      h3.col.px-4.mb-0.text-white(data-aos="fade-right") Validacion del rendimiento
    .bloque1.p-0.mb-5

        .bloque-texto-b__texto
          .row.justify-content-center.align-items-center.d-flex
              .col-lg-6.col-12
                p.mb-lg-0.mb-3 Los puntos de conexión inalámbricos IoT trabajan durante años y logran instalarse fácilmente en el lugar deseado. Con la aparición continua de nuevas aplicaciones esto puede implicar que estas terminales deban usarse en ambientes de RF realmente adversos. Los medidores inteligentes instalados en bodegas o sótanos, por ejemplo, tienen que hacer frente a condiciones complicadas de cobertura. Nuevos dispositivos, como los sensores de estacionamiento, deben ser muy fuertes y resistentes al agua, lo cual es un gran desafío para el diseño de RF global. El rendimiento de las conexiones inalámbricas de los dispositivos IoT es un factor crucial para el éxito de las aplicaciones del IoT y requiere de atención al detalle, así como de un tiempo y esfuerzo considerables. 
              .col-lg-6.col-8.px-5
                img.mb-0(alt="" src="@/assets/curso/temas/tema3/validacion.jpg") 
    .d-flex.flex-wrap.align-items-center.pe-4(style="background-color: #083142; border-radius: 25px; padding: 10px")
      img.col-lg.d-none.d-lg-flex(src='@/assets/curso/temas/tema3/esquina.svg' style="max-width: 70px; left: 16px; position: absolute" data-aos="fade-left")
      h3.col.px-4.mb-0.text-white(data-aos="fade-right") Documentación de pruebas y resultados 
    .bloque1.p-0.mb-5
      .bloque-texto-b.color-secundario.p-4.mb-0(data-aos="fade-left")
        .bloque-texto-b__texto
          .row.justify-content-center.align-items-center.d-flex
              .col-lg-10.col-12
                p.mb-lg-0.mb-3 Un dispositivo IoT, como su nombre indica, es un dispositivo que se conecta a internet para realizar alguna operación, ya sea almacenar datos, consultar un servicio, etc.<br><br>Las pruebas loT, permite al usuario controlar dispositivos de forma remota a través de una red. El IoT testing es un nuevo enfoque de prueba que involucra un alcance más amplio y complejo de pruebas de software tradicionales.  
              .col-lg-2.col-8.px-5
                img.mb-0(alt="" src="@/assets/curso/temas/tema3/documentacion.svg")   
                

    p El enfoque de prueba IoT puede ser diferente según el sistema/arquitectura involucrado, observemos como:
              
    figure.mb-4(data-aos="zoom-in")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/iSWz9b7HCEo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    Separador 
    

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

<style lang="sass"></style>
