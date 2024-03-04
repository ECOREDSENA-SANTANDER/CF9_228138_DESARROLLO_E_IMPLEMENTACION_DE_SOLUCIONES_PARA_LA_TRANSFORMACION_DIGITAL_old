<template lang="pug">
.curso-main-container.pb-3.tema8
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
      .titulo-principal.color-acento-botones
        .titulo-principal__numero
          span 1
        h1 Lenguaje de programación orientado a objetos

      .cajon-b.color-secundario.mb-4.py-0
        .row.align-items-center.justify-content-center
          .col-auto.my-3
            img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/tema1/lenguaje.svg', alt='')
          .col-9.my-3
            p(data-aos="fade-down") La programación orientada a objetos se conoce como un paradigma o un modelo de programación, no es un lenguaje específico, o una tecnología sino una forma específica de programar, más cercana a cómo expresaremos las cosas en la vida real que otros lenguajes de programación.  

          p(data-aos="fade-down") Lenguajes modernos como Java, C# y Python, utilizan paradigmas para definir los programas, siendo las más populares dentro de la POO esta aprueba que el código sea reutilizable, organizado y fácil de conservar. Alcanza el principio de desarrollo de software manejado por varios programadores(Roman, 2013). 
          br
          p El primer y más importante concepto que debemos tener en cuenta de la POO es la distinción entre clase y objeto.  
          .mb-4.d-flex
      .d-flex.flex-wrap.align-items-center.pe-4(style="background-color: #083142; border-radius: 25px; padding: 10px")
          img.col-lg.d-none.d-lg-flex(src='@/assets/curso/temas/tema1/titulo.png' style="max-width: 70px; left: 16px; position: absolute" data-aos="fade-left")
          h3.col.px-4.mb-0.text-white(data-aos="fade-right") Una clase
      .fondo1.py-lg-5.py-3
        .row.justify-content-center.align-items-center.mb-0.position-relative(data-aos="fade-left")
        .bloque1.p-0
        .bloque-texto-b.color-secundario.p-2.mb-0(data-aos="fade-left")
          .bloque-texto-b__texto
      .row.justify-content-center.align-items-center.d-flex
        .col-lg-9.col-9.mb-9.mg-lg-0
                p Es una lista genéricamente de cómo van a ser los objetos de un determinado tipo.  
                p Por ejemplo, una clase para personificar a animales puede llamarse ‘animal’ y poseer una serie de atributos, como ‘nombre’ o ‘clase de animal’ (que regularmente son propiedades) y una sucesión con las actuaciones que estos pueden tener, como comer o correr, y que a su vez se efectúan métodos de la clase siendo (funciones) 
        .col-lg-2.col-4
            img.mb-lg-0.mb-3(alt="" src="@/assets/curso/temas/tema1/img03.svg")
        .col-lg-8.col-12
        .mb-4.d-flex
      .d-flex.flex-wrap.align-items-center.pe-4(style="background-color: #083142; border-radius: 25px; padding: 10px")
          img.col-lg.d-none.d-lg-flex(src='@/assets/curso/temas/tema1/titulo.png' style="max-width: 70px; left: 16px; position: absolute" data-aos="fade-left")
          h3.col.px-4.mb-0.text-white(data-aos="fade-right") Un objeto
      p.mb-3 Se puede ver en el gŕafico 1. Una entidad “perro” ,”gato”, “ardilla” tiene una clase asociada “animal”. Está clase animal posee unas características propias que lo distinguen unos de otros, por ejemplo, edad , nombre, raza , entre otros. A su vez, el animal tiene acciones como “comer”, “dormir” y “correr” .  
      
      .row.justify-content-center.mb-4
        .col-lg-10
      .t
      .titulo-sexto.color-acento-contenido.mb-4(data-aos="fade-right")
            h5 Figura 1 
            span Ejemplo POO  

      
      .row.justify-content-center.align-items-center.mb-5
        .col-lg-7.col-10.mb-lg-0.mb-4(data-aos="fade-right")
          img(src="@/assets/curso/temas/tema1/img01.jpg")
        .col-lg-5(data-aos="fade-left")
          p A partir de está clase se pueden crear las instancias, es decir, cuando la clase cuenta con memoria en el sistema operativo que va a operar sobre el software.<br><br> De está forma, se pueden crear las instancias para un Perro de nombre=”Yoni”  con una edad de “5” años o bien la representación de un gato de nombre=”Milu” y de edad=”1” año.  Los dos están a partir de la clase animal, pero son dos instancias diferentes. Por lo que al llamar a sus métodos logra poseer resultados diferentes. Los dos comparten la lógica de sus requerimientos funcionales, pero cada uno de forma independiente tiene su estado.
        p.mb-0 En estos términos, la programación orientada a objetos ofrece una forma de abstraer entidades del mundo real, a partir de cuatro(4) principios a nombrar:
      
      .tarjeta.tarjeta--azul.p-4
        SlyderA(tipo="b")
          .row.justify-content-center.align-items-center.my-lg-8
            .col-md-5
              h3 La encapsulación
              p Un objeto oculta sus datos y solo muestra (interfaz) u ofrece un servicio al universo de las clases. De está forma, “el gato Milu corre”, una clase que representa una veterinaria podría operar sobre ella, sabiendo que “Milu” corre pero desconociendo cuál es su proceso funcional.
          .row.justify-content-center.align-items-center.my-lg-8
            .col-md-5
              h3 La abstracción
              p  Es la formalización del objeto en la clase. ¿Qué es un animal?, ¿cómo identificar un animal?, ¿Qué acciones hace un animal?. Con estas respuestas , creó la clase, atributos y sus correspondientes atributos.  
            

          .row.justify-content-center.align-items-center.my-lg-8
            .col-md-5
              h3 La herencia
              p Clases que dependen del concepto de “es hijo de”, “es relacionado con”, “compartes datos con”. Hace referencia al concepto semántico de “herencia”, es decir, entidades que tienen los atributos de sus padres. A partir del ejemplo, se podría crear una clase “mamífero” a partir de la clase “animal”, ya que todos los mamíferos son animales y comparten los mismos atributos.
        
        
          .row.justify-content-center.align-items-center.my-lg-8
            .col-md-5
              h3 El polimorfismo
              p Capacidad que tienen las clases y/u operaciones para hacer la misma función en diferentes contextos o dominios. En el caso particular, no es lo mismo “comer para un perro” que “comer para un gato”, los dos objetos tendrán el mismo método pero diferente acción sobre.
      .row.justify-content-center.align-items-center.mb-5
        .col-lg-5.col-10.mb-lg-0.mb-4(data-aos="fade-right")
          img(src="@/assets/curso/temas/tema1/img08.png")
          .mb-4.d-flex
      .d-flex.flex-wrap.align-items-center.pe-4(style="background-color: #083142; border-radius: 25px; padding: 10px")
          img.col-lg.d-none.d-lg-flex(src='@/assets/curso/temas/tema1/titulo.png' style="max-width: 70px; left: 16px; position: absolute" data-aos="fade-left")
          h3.col.px-4.mb-0.text-white(data-aos="fade-right") C++
          BR
      p Es un lenguaje de programación orientado a objetos. Los cuatro principios básicos de la programación orientada a objetos son: Abstracción: modelar los atributos e interacciones pertinentes de las entidades como clases para definir una representación abstracta de un sistema.
      .row.justify-content-center.align-items-start.mb-5
      .col-lg-12
        img.img-a.img-t.mb-5(data-aos="zoom-in")(src='@/assets/curso/temas/tema1/img09.png', alt='')
        .mb-4.d-flex
      .d-flex.flex-wrap.align-items-center.pe-4(style="background-color: #083142; border-radius: 25px; padding: 10px")
          img.col-lg.d-none.d-lg-flex(src='@/assets/curso/temas/tema1/titulo.png' style="max-width: 70px; left: 16px; position: absolute" data-aos="fade-left")
          h3.col.px-4.mb-0.text-white(data-aos="fade-right") JAVA (SE,EE)
      p Oracle Java es la plataforma de lenguaje de programación y desarrollo, que reduce costos, acorta los plazos de desarrollo, impulsa la innovación y mejora los servicios de las aplicaciones, conozcamos más:
      
      .row(data-aos="zoom-in")
      .col-lg-12.mb-2
        AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--gris")
          .row(titulo="Plataforma informática Java")
            .col-12.ps-5
              ul.lista-ul--color.lista-acento-botones.mb-0
                li.mb-0.d-flex 
                  p.mb-0 Java es un lenguaje de programación que opera por medio de una plataforma informática Java, hay cuatro ediciones principales de Java: Java Standard Edition (Java SE) Java Enterprise Edition (Java EE) Java Micro Edition (Java ME) 
          .row(titulo="Evoluciones")
            .col-12.ps-5
              ul.lista-ul--color.lista-acento-botones.mb-0
                li.mb-0.d-flex 
                  p.mb-0 Ha tenido constantes evoluciones desde sus inicios, Java nace en 1991 con el nombre “OAK”, posteriormente cambiado por Green por problemas legales, y finalmente con la denominación actual JAVA.<br><br>El objetivo de Java era crear un lenguaje de programación parecido a C++ en estructura y sintaxis, fuertemente orientado a objetos, pero con una máquina virtual propia.
          .row(titulo="Aplicaciones Java modernas")
            .col-12.ps-5
              ul.lista-ul--color.lista-acento-botones.mb-0
                li.mb-0.d-flex 
                  p.mb-0 Concientizan el tiempo de ejecución y la aplicación de Java, para su correcto funcionamiento se debe instalar Java para escritorio. Encontramos muchas aplicaciones del lenguaje Java en casi todos los campos, ya sea una aplicación o desarrollo web, big data, Inteligencia Artificial, desarrollo móvil, etc
          .row(titulo="Sitio web Java.com")
            .col-12.ps-5
              ul.lista-ul--color.lista-acento-botones.mb-0
                li.mb-0.d-flex 
                  p.mb-0 Oracle Java está disponible en el Acuerdo de licencia de Oracle Technology Network para Oracle Java SE. Esta licencia permite utilizar Java con fines personales y de desarrollo de forma gratuita.<br><br>Java 18 (Oracle JDK 18) ofrece miles de mejoras en cuanto a rendimiento, estabilidad y seguridad, incluyendo nueve propuestas de mejora de la plataforma, impulsando así aún más la productividad de los desarrolladores.
          .row(titulo="Java EE")
            .col-12.ps-5
              ul.lista-ul--color.lista-acento-botones.mb-0
                li.mb-0.d-flex 
                  p.mb-0 Es escalable para los proyectos, es decir, permite acoplar más tecnologías según vayan dándose las necesidades del software. Y Java SE es Edición Estándar.                              
          .row(titulo="Requisitos para programar Java")
            .col-12.ps-5
              ul.lista-ul--color.lista-acento-botones.mb-0
                li.mb-0.d-flex 
                  p.mb-0 Debe tener una sólida comprensión de la programación orientada a objetos. Estar familiarizado con varios diseños y patrones arquitectónicos. Habilidad para escribir bibliotecas en lenguaje Java reutilizables. Conocimiento de los patrones de concurrencia en Java.
          .row(titulo="Aplicación de uso personal")
            .col-12.ps-5
              ul.lista-ul--color.lista-acento-botones.mb-0
                li.mb-0.d-flex 
                  p.mb-0 Si quiere descargar la aplicación de uso personal es gratuita donde se contará con todos los kits de desarrollo y herramientas útiles y compatibles. Para instalar java puede consultar el siguiente tutorial en línea:<br><br>https://www.java.com/es/download/help/windows_manual_download.html.<br><br> En la plataforma Link: https://www.jdoodle.com/online-java-compiler/



      .mb-4.d-flex
      .d-flex.flex-wrap.align-items-center.pe-4(style="background-color: #083142; border-radius: 25px; padding: 10px")
          img.col-lg.d-none.d-lg-flex(src='@/assets/curso/temas/tema1/titulo.png' style="max-width: 70px; left: 16px; position: absolute" data-aos="fade-left")
          h3.col.px-4.mb-0.text-white(data-aos="fade-right") PHP 
      p.mb-0 Es un lenguaje de código abierto muy reconocido sobre todo para el desarrollo web ya que el mismo puede ser fácilmente incrustado en HTML, una de las grandes ventajas es su simplicidad para aquellos desarrolladores principiantes, por medio de este lenguaje se generan páginas web dinámicas que frecuentemente su contenido cambia, debemos tener en cuenta que las páginas webs estáticas son las que sus contenidos permanecen siempre igual.<br><br>
      p El esquema de php funciona mediante una petición al servidor el mismo recibe la información necesaria realizando las consultas a bases de datos, otros servidores u otras páginas web, el servidor responde si es una página web normal estática, pero donde el diseño y creación del mismo ha sido dinámico.
      .row.justify-content-center.align-items-start.mb-5
        .col-lg-10
          img.img-a.img-t.mb-5(data-aos="zoom-in")(src='@/assets/curso/temas/tema1/php.png', alt='')

      .mb-4.d-flex
      .d-flex.flex-wrap.align-items-center.pe-4(style="background-color: #083142; border-radius: 25px; padding: 10px")
          img.col-lg.d-none.d-lg-flex(src='@/assets/curso/temas/tema1/titulo.png' style="max-width: 70px; left: 16px; position: absolute" data-aos="fade-left")
          h3.col.px-4.mb-0.text-white(data-aos="fade-right") Ruby
      p.mb-0 Ruby es un lenguaje de programación interpretado, abstraído y orientado a objetos su licencia es distribuida bajo software libre, todos los tipos de datos son con objeto, clases, métodos, es descrito como un lenguaje multiparadigma, permitiendo programación procedimental.  

      .row.justify-content-center.align-items-center.mb-5
        .col-lg-7.order-lg-1.order-0(data-aos="fade-right")
          .bloque-texto-b.color-secundario.p-4
            .bloque-texto-b__texto
              i.fas.fa-quote-left(style="font-size: 2em")
              p.mb-0 Se utiliza en su mayoría en el desarrollo de aplicaciones web, pero también se utiliza para otros tipos de desarrollo en streaming. Ruby maneja estrechamente el paradigma de POO, así que estas variables son privadas y no logran verse desde fuera de la clase, toda comunicación que se realiza entre objetos se hace con los métodos. Se caracteriza por un lenguaje dinámico, ya que los programas en Ruby no se compilan, todo el código de clases, módulos y métodos se realiza por medio de un intérprete.<br>(Cupul, 2021)..

              i.fas.fa-quote-right(style="font-size: 2em")
        .col-lg-5.col-10.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
            img(src="@/assets/curso/temas/tema1/ruby.png") 
      .row.justify-content-center.align-items-center.mb-5
        .col-lg-4.col-6.order-lg-2.order-1.mb-lg-4.mb-4(data-aos="fade-left")
                img(src="@/assets/curso/temas/tema1/ruby2.png") 
      
                .mb-4.d-flex
      .d-flex.flex-wrap.align-items-center.pe-4(style="background-color: #083142; border-radius: 25px; padding: 10px")
          img.col-lg.d-none.d-lg-flex(src='@/assets/curso/temas/tema1/titulo.png' style="max-width: 70px; left: 16px; position: absolute" data-aos="fade-left")
          h3.col.px-4.mb-0.text-white(data-aos="fade-right") Python
                .row

      .bloque-texto-b.color-secundario.p-4
          .bloque-texto-b__texto
            i.fas.fa-quote-left
            p.mb-0 Python Es un lenguaje de programación considerablemente utilizado en la mayor parte de las aplicaciones web, al realizar programas empresariales, la ciencia de datos y el machine learning (ML). Los programadores utilizan Python porque es eficientemente muy fácil de aprender, además de que se puede ejecutar en diferentes plataformas. El software Python es gratuito, se integra bien a todos las características de sistemas y aumenta la velocidad del desarrollo.
            p.mb-0 (S & G, 2018)
            i.fas.fa-quote-right
      p Las empresas requieren programadores expertos en Python esto debido que es más fácil con tecnologías emergentes como:
      figure.mb-4(data-aos="zoom-in")
        .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/iSWz9b7HCEo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
