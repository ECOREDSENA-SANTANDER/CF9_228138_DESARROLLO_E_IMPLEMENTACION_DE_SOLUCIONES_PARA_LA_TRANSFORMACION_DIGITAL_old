<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Conceptos asociados al lenguaje

    .row.justify-content-center
      .col-lg-5.col-5.mb-4.mb-lg-0(data-aos="zoom-in")
        figure
          img(src='@/assets/curso/temas/tema2/img001.jpg', alt='imagen decorativa') 

      .col-lg-7.mb-4.mb-md-0(data-aos="fade-left")
        p Pudimos analizar que en cada lenguaje de programación la lógica es la misma pero los conceptos de cada uno pueden cambiar. Los lenguajes de programación se podrían definir como el proceso donde se crea, depura y compila creando programas de computadora, la misma se realiza por código o instrucciones que el desarrollador realiza en un lenguaje de computadora se cuenta con lenguajes de programación fuertes, de bajo medio o alto nivel, compilados, y declarativos u orientado a objetos.<br><br> Para iniciar a programar debemos tener los conceptos básicos de programación, como: 
    .bg--deep-orange.br_01.p-5(data-aos="zoom-in")
        SlyderA(tipo="b")
    .row.justify-content-center.align-items-center
      .col-lg-8.mb-4.mb-md-0
        h3 Algoritmo
        p Son la base de programación. Dominando los algoritmos te ayudan a buscar soluciones en cualquier lenguaje de programación.
      .col-lg-2
        figure
        img(src='@/assets/curso/temas/tema2/Algoritmo.svg', alt='')

    .row.justify-content-center.align-items-center
      .col-lg-8.mb-4.mb-md-0
        h3 Variable
        p Son unidades de almacenamiento datos que se utilizan para programar, se almacenan en espacios reservados en la memoria RAM.
      .col-lg-2
          figure
          img(src='@/assets/curso/temas/tema2/Variable.svg', alt='')

    .row.justify-content-center.align-items-center
      .col-lg-8.mb-4.mb-md-0
          h3 Funcion
          p Son bloques que realizan tareas específicas el comando es function, se reutiliza código ya que ahorra tiempo al redactar líneas.
      .col-lg-2
          figure
          img(src='@/assets/curso/temas/tema2/Funcion.svg', alt='')

    .row.justify-content-center.align-items-center
      .col-lg-8.mb-4.mb-md-0
            h3 Tipos de datos
            p Los tipos son enteros o número como (1,2022), float (3,6), string cadena de texto “Programa”, boolean cuando se tiene dos opciones sí o no False o true.
      .col-lg-2
            figure
            img(src='@/assets/curso/temas/tema2/Tipos.svg', alt='')


    Separador    
    #t_2_1.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 2.1 Sintaxis
    p(data-aos="fade-down").mb-5 La sintaxis dentro de todo lenguaje de programación es la combinación de reglas y símbolos que se consideran declaraciones o expresiones estructuradas en un lenguaje de programación.<br><br>Ideas principales y los puntos de conexión : 
      
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-7(data-aos="fade-left")
        .bloque-texto-c.color-secundario.p-4

          p Describe a la escritura del código  
          p Enfrenta a la semántica en sí el significado.  
          p El método semántico suele ser posterior al sintáctico  
          p El método semántico es necesario para completar el análisis sintáctico, y se realizan juntos o al mismo tiempo. 
          p Ruby es un lenguaje orientado a objetos, su sintaxis y semántica presentan que en su mayoría todos los tipos son objetos. 
          p Muchos operadores son métodos de los objetos(Aprendiendo Ruby y Rails. Parte 1. Introducción a Ruby, 2015.) 
      .col-lg-5.col-10.mb-lg-0.mb-4(data-aos="fade-right")
        img(src="@/assets/curso/temas/tema2/img2.1.svg")  
    
    Separador    
    #t_2_2.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 2.2 Estructura general del lenguaje 
    .row.align-items-center.justify-content-center.mb-4
      .col-lg-5.my-2
        img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/tema2/estructura.jpg', alt='')
      .col-lg-7.my-3
        .bloque-texto-b.color-#FFF3EA.p-4.mb-4
          .bloque-texto-b__texto
            i.fas.fa-quote-left
          p.mb-0 Un programa informático es una serie de acciones (instrucciones o comandos) que manejan un conjunto de objetos (datos e información), depende mucho el lenguaje que estés manejando para conformar su estructura. Los bloques que existen son declaraciones e instrucciones<br><br><b>(Inicio - Introducción a Ruby, 2018.)</b> 
            i.fas.fa-quote-right
          p(data-aos="fade-down") Las declaraciones son los objetos que utiliza el programa como variables y archivos (Variables, archivos, etc) las instrucciones son los resultados que se esperan por las acciones y operaciones realizadas. En la figura 2, presenta la estructura básica de un programa en Ruby.
          
    .row.justify-content-center(data-aos="fade-right")
      .col-lg-4.col-12.d-flex
        .tarjeta--boton.color-primario.p-4(style="background-color: #FED9D3; border-radius: 20px; padding: 100px")
          .row.justify-content-center.mb-3
            .col-6
              figure
                img(src='@/assets/curso/temas/tema2/entrada.svg',)

          h3.text-center Entrada de datos
          p.text-small Almacenan en la memoria interna datos procedentes de un dispositivo externo.
  
      .col-lg-4.col-12.d-flex
        .tarjeta--boton.color-primario.p-4(style="background-color: #FED9D3; border-radius: 20px; padding: 100px")
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/tema2/proceso.svg',)

          h3.text-center Proceso o algoritmo
          p.text-small  Instrucciones que modifican los objetos de entrada y, en ocasiones, creando otros nuevos.

      .col-lg-4.mb-4.mb-lg-0
        .tarjeta--boton.color-primario.p-4(style="background-color: #FED9D3; border-radius: 20px; padding: 100px")
          .row.justify-content-center.mb-3
            .col-9
              figure
                img(src='@/assets/curso/temas/tema2/salida.svg',)

          h3.text-center Salida de resultados
          p.text-small  Conjunto de instrucciones que toman los datos finales de la memoria interna y los envían a los dispositivos externos.
    p.mb-5 La estructura basica de un programa informatico se muestra en la tabla 1. 
          
    .row.justify-content-center.mb-4
      .col-lg-10
        .t
        .titulo-sexto.color-acento-contenido.mb-4(data-aos="fade-right")
          h5 Tabla 1
          span Ejemplo de aplicación técnica de puntos de historia y valor del negocio
        
        .tabla-b.color-acento-#F6F6F6
          table
            tr
              th(style="background-color: #FED9D3;") Cabecera 
              td(style="background-color: #FED9D3;") Se especifica por medio del nombre de programa, los datos de entrada y datos de salida.
            tr
              th(style="background-color: #fff;") Funciones 
              td(style="background-color: #fff;") Son las diseñadas por el desarrollador y se usa las ocasiones necesarias.
            tr
              th(style="background-color: #FAF0EF;") Declaraciones 
              td(style="background-color: #FAF0EF;") Las mismas se definen en los tipos de variables, constantes y los nuevos tipos de datos que se den.
            tr
              th(style="background-color: #fff;") Asignaciones 
              td(style="background-color: #fff;") Valores iniciales declarados previamente.
            tr
              th(style="background-color: #FAF0EF;") Entradas 
              td(style="background-color: #FAF0EF;") Almacenan en memoria algunos valores.
            tr
              th(style="background-color: #fff;") Control 
              td(style="background-color: #fff;") Las mismas pueden ser alternativas y repetitivas  
            tr
              th(style="background-color: #FAF0EF;") Salidas 
              td(style="background-color: #FAF0EF;") Son las que muestran los resultados obtenidos.
        

    Separador    
    #t_2_3.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 2.3 Editores de código
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-6(data-aos="fade-right")
      p(data-aos="fade-down").mb-5 A medida de los grandes avances de la tecnología en plena cuarta revolución industrial los programas de computadora que nos ayuda a realizar código fuentes de los diferentes proyectos de programación y se pueden alternar varios lenguajes o editores en un mismo proyecto, ya que en un proyecto de comercio electrónico se puede combinar lenguajes como Python, JavaScript, php, HTML, etc. Los mismos evolucionan constantemente, muchos usuarios crean página web sin tener conocimientos en programación, pero sí requiere paginas webs profesionales, existen editores de código que funcionan perfectamente en sistemas operativos como Windows, MacOs o Linux. <br><br>
      .col-lg-1.col-8.mb-4.mb-lg-0
        img(src='@/assets/curso/temas/tema2/img003.svg')
      .col-lg-6(data-aos="fade-right")
        p Las características de los editores de código en cada sistema operativo son, capacidad de almacenar proyectos, sintaxis en varios idiomas, funciones de búsqueda y reemplazo, funciones de mostrar y ocultar secciones, edición de macros. Algunos editores son: 
        
    .row    
      .d-flex.flex-wrap.align-items-center.pe-4(style="background-color: #EFEFEF; border-radius: 00px; padding: 60px")
      .col-lg-8    
        p  Coda: es una aplicación web que funciona como editor de código para MacOS. 
        p Notepad++: es un editor versátil y soporta lenguajes como HTML, JavaScript y php. 
        p Visual Studio code: es desarrollado por Microsoft se usa con diferentes lenguajes de programación, incluidos C (C, C ++, C #), F #, HTML entre otros, incluidos PHP, Java, Ruby y muchos otros. Une un conjunto de funciones que se reforman según el idioma que esté utilizando. 
        p Atom: es un editor de javascript ligero y tiene una gran cantidad de extensiones donde se puede personalizar su funcionamiento. 
        p Ultraedit: es uno de los lenguajes donde se puede editar multitud de lenguajes de programación en HTML; Javascript, ASP.
      .col-lg-3.col-8.mb-lg-0.mb-4(data-aos="fade-left")
          img(src="@/assets/curso/temas/tema2/img004.jpg")




    Separador    
    #t_2_4.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 2.4 Conexiones a bases de datos
      <br>
    .row.justify-content-center  
      .col-lg-2.col-2.mb-2.mb-lg-2
        img.img-a.img-t.mb-5(data-aos="zoom-in")(src='@/assets/curso/temas/tema2/conexion.svg', alt='')
      .col-lg-10.mb-8.mb-md-0(data-aos="fade-left")
          p(data-aos="fade-down").mb-5 Una conexión de base de datos es un registro de configuración en el que se especifican los detalles físicos de una base de datos, como el tipo de base de datos y la versión, y los parámetros para habilitar una conexión. Desde una aplicación por ejemplo en entornos web , se puede concebir la interacción con la base de datos a partir del gŕafico 3, donde existe un client que invoca una petición a la aplicación web que está alojado en un servidor web y desde ahí, el backend de la aplicación interactúa con la base de datos respectiva, generando todos los accesos y dan resultados de nuevo al core de la webapp y de allí mostrar resultados a las vistas (frontend) del cliente respectivo.
    .row
      .col-lg-6.mb-4.mb-lg-0(data-aos="zoom-in")
        figure
          img(src='@/assets/curso/temas/tema2/img002.jpg', alt='imagen decorativa')  

      .col-lg-6(data-aos="fade-left")
        .bg--acento-contenido.br_cstm.p-4
          p Una base de datos permite acumular gran número de información de una forma constituida para su futura consulta, construcción de búsquedas, nuevo ingreso de datos, etc. Todo esto lo aprueba si se realiza de una forma rápida y simple desde un computador.<br><br>En proyectos de IOT en la nube se pueden adquirir servicios de base de datos como Amazon y Dynamo DB.<br><br>Los componentes de una base de datos.

</template>
<script>
export default {
  name: 'Tema2',
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
