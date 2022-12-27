<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Aplicaciones web

    p(data-aos="fade-down").mb-5 En la historia de la computación la web sin duda fue el acontecimiento que marcó el hito más importante para la popularidad y el aumento del uso de la internet, que ya venía naciendo entre los años 60 y 70 del siglo pasado, pero no había tenido relevancia más allá de los proyectos científicos, las grandes corporaciones, los académicos y los militares; sin embargo, no fue hasta década y media después que con la creación de la World Wide web publicada en 1990 por el inglés Tim Berners-Lee permitió su popularidad y su funcionalidad, pues aumentó el uso a través de los navegadores (<i>browser</i>). 

    .row.align-items-center.justify-content-center
      .col-lg-10 
        .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/2.jpg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Las aplicaciones web son, entonces, los servicios que se desarrollan en la web, implicando el despliegue de un conjunto de <i>software</i>, tecnologías y plataformas que soportan su funcionamiento, comunicación y transmisión. 

    p(data-aos="fade-down").mb-5 Los diversos servicios web intercambian datos entre sí para ofrecer servicios más sofisticados y específicos. Esto sucede bajo una arquitectura básica, donde los proveedores brindan servicios remotos que podrían ser solicitados por usuarios a través de llamados que llegan al cliente, todo por medio de la web.  

    Separador 
    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 1.1  Componentes

    .cajon-b.color-acento-contenido.mb-4.py-2
      .row.align-items-center.justify-content-center
        .col-auto.my-3
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/3.svg', alt='')  
        .col-10.my-3
          p(data-aos="fade-down") Existen diversos elementos que son importantes de entender, si bien no son nuevos, son la fundamentación tecnológica que soporta el funcionamiento de los aplicativos basados en la web y su funcionamiento en la internet. 

          p(data-aos="fade-down") A continuación se mencionan los aspectos más relevantes que todo profesional de la digitalización y la transformación tecnológica debe conocer y estudiar, donde cada elemento implica una arquitectura y una capa en el funcionamiento de la internet a través de la web .
                       	              
    .bg1.p-4.mb-5(data-aos="fade-left")
      SlyderA(tipo="b")
        .row.align-items-center.justify-content-center
          .col-lg-6.col-md-12.my-3
            img.img-a.img-t(src='@/assets/curso/temas/4.png', alt='')  
          .col-lg-6.col-md-12.my-3
            h4.mb-4 WWW	
            p Son las iniciales de Word Wide web, por lo general se colocan estas tres letras para indicar al navegador que se trata de un aplicativo web, que se despliega mediante el protocolo HTTP.
        .row.align-items-center.justify-content-center
          .col-lg-6.col-md-12.my-3
            img.img-a.img-t(src='@/assets/curso/temas/5.png', alt='')  
          .col-lg-6.col-md-12.my-3
            h4.mb-4 HTTP	
            p Son las siglas de Hypertext Transfer Protocol que significa protocolo de comunicación para la transferencia de hipertexto, usado en las aplicaciones web.
        .row.align-items-center.justify-content-center
          .col-lg-6.col-md-12.my-3
            img.img-a.img-t(src='@/assets/curso/temas/6.png', alt='')  
          .col-lg-6.col-md-12.my-3
            h4.mb-4 IP
            p Son las siglas de internet Protocol que significa Protocolo de internet, es un protocolo de comunicación, de la capa de red, que se responsabiliza de las direcciones IP y determina las rutas de salida y llegada de los paquetes de datos que van y vienen. Cada página web cuenta con una dirección IP única, desde la línea de comando puede conocerla mediante el comando <i>ping</i> a la página web.
        .row.align-items-center.justify-content-center
          .col-lg-6.col-md-12.my-3
            img.img-a.img-t(src='@/assets/curso/temas/7.png', alt='')  
          .col-lg-6.col-md-12.my-3
            h4.mb-4 DNS	
            p Es el sistema traduce los nombres de los dominios, por ejemplo, www.sena.edu.co a direcciones IP aptas para la lectura por parte de las máquinas (ejemplo: 186.113.6.24). Desde la línea de comandos puede usar la herramienta <i>nslookup</i> seguido de la dirección web.
        .row.align-items-center.justify-content-center
          .col-lg-6.col-md-12.my-3
            img.img-a.img-t(src='@/assets/curso/temas/8.png', alt='')  
          .col-lg-6.col-md-12.my-3
            h4.mb-4 URL
            p Son las siglas de Uniform Resource Locator que significa Localizador de recursos uniforme, se trata de la dirección única que se asigna a cada recurso de una web. Esta URL la usan los navegadores y los usuarios para llegar a una web o a un lugar específico de esta.
        .row.align-items-center.justify-content-center
          .col-lg-6.col-md-12.my-3
            img.img-a.img-t(src='@/assets/curso/temas/9.png', alt='')  
          .col-lg-6.col-md-12.my-3
            h4.mb-4 HTML
            p Son las siglas de HyperText Markup Language que significa lenguaje de marcado de hipertexto, es el lenguaje ‘nativo’ que se utiliza en los sitios web y lo traduce el explorador o navegador para mostrar los contenidos. Actualmente, la web no solo usa HTML, se complementa con estilos (CSS), JavaScript, XML y otros recursos de programación.
        .row.align-items-center.justify-content-center
          .col-lg-6.col-md-12.my-3
            img.img-a.img-t(src='@/assets/curso/temas/10.png', alt='')  
          .col-lg-6.col-md-12.my-3
            h4.mb-4 XML	
            p Son las siglas de Extensible Markup Language que significa lenguaje de marcado extensible, se emplea para enviar o recibir información de otros sistemas y para integrar las plataformas de información. Es un lenguaje que comparte datos de un sistema a otro.
        .row.align-items-center.justify-content-center
          .col-lg-6.col-md-12.my-3
            img.img-a.img-t(src='@/assets/curso/temas/11.png', alt='')  
          .col-lg-6.col-md-12.my-3
            h4.mb-4 Navegador web o <i>browser</i>	
            p Es la aplicación tipo cliente que permite el acceso y la carga de los sitios web, interpreta la información enviada por servidores y permite la visualización al usuario final. Actualmente los navegadores más populares en su orden son: Chrome, Safari, Edge, Firefox, Android.
                                                                              Separador 
    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 1.2  Plataformas          
    p(data-aos="fade-down").mb-5 Son espacios en la internet que ejecutan diversas aplicaciones, servicios o programas, estos permiten la virtualización de servicios especializados, ahorrando tiempo de desarrollo y optimizando los recursos, pues las organizaciones solo deben concentrarse en su acción misional sin preocupaciones por las herramientas digitales o contratar personas especializadas, e incluso contar con mayor flexibilidad al momento de cambiar de proveedor si no satisface los requerimientos o las necesidades.

    .row.align-items-center.justify-content-center.mb-5
      .col-auto
        .bg2.p-2.text-center.px-5
          p(data-aos="fade-down").mb-0 Las plataformas web podrían clasificarse según el uso requerido de la siguiente manera : 

    TabsB.color-acento-contenido.mb-5(data-aos="fade-right")
      .py-4.py-md-5(titulo="Plataformas sociales" :icono="require('@/assets/curso/temas/12.png')")
        .row.align-items-center.justify-content-center
          .col-lg-10
            img.img-a.img-t.mb-4(src='@/assets/curso/temas/16.png', alt='')
            p Quizás las más usadas masivamente, se relacionan directamente con las redes sociales, y su funcionalidad es guardar y gestionar la información referente a las interacciones.
      .py-4.py-md-5(titulo="Plataformas educativas" :icono="require('@/assets/curso/temas/13.png')")
        .row.align-items-center.justify-content-center
          .col-lg-10
            img.img-a.img-t.mb-4(src='@/assets/curso/temas/17.png', alt='')
            p Se trata de plataformas LMS (Learning Management System - sistema de gestión del aprendizaje) y otras, que se concentran en gestionar contenido educativo y usuarios con sus roles correspondientes, en estas se crean cursos, materiales de formación, se gestionan exámenes, certificados y todo lo relacionado tanto con lo académico como con lo administrativo.
      .py-4.py-md-5(titulo="Comercio electrónico (<i>e-commerce</i>)" :icono="require('@/assets/curso/temas/14.png')")
        .row.align-items-center.justify-content-center
          .col-lg-10
            img.img-a.img-t.mb-4(src='@/assets/curso/temas/18.png', alt='')
            p Son plataformas dedicadas a las ventas, a través de estas las personas pueden averiguar, cotizar y comprar desde internet, permitiendo que la masificación de transacciones y compras <i>online</i> venga en aumento en Latinoamérica y especialmente en Colombia.
      .py-4.py-md-5(titulo="Computación en la nube (<i>Cloud computing</i>)" :icono="require('@/assets/curso/temas/15.png')")
        .row.align-items-center.justify-content-center
          .col-lg-10
            img.img-a.img-t.mb-4(src='@/assets/curso/temas/19.png', alt='')
            p Este tipo de plataformas son ecosistemas digitales donde conviven con otras plataformas de negocio. Ofrecen múltiples servicios TI con arquitecturas basadas en la nube a través de servidores remotos, cuyos propietarios, por lo general, son los proveedores de estos servicios.    

    .row.align-items-center.justify-content-center.mb-5
      .col-lg-10
        .bg3.p-4
          .row.align-items-center.justify-content-center
            .col-lg-7.my-3
              p(data-aos="fade-down") Para cada necesidad existe una o muchas plataformas web que permiten desarrollar fácilmente lo que se requiera, ya sea para el desarrollo web o de aplicaciones, <i>marketing</i>, diseño e imagen, diversión y juegos, apuestas, gestión de proyectos, etc.

              p(data-aos="fade-down").mb-0 Todas las plataformas han tenido un crecimiento importante, las opciones en el mercado son múltiples y con muy buenas prestaciones, antes de iniciar proyectos web enmarcados en una actividad específica, no está de más realizar investigaciones previas a los proyectos para definir las mejores opciones para las organizaciones.                
            .col-lg-5.my-3
              img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/20.png', alt='')  

    p(data-aos="fade-down").mb-5 Generalmente, lo que se proyecta o plantea desarrollar en las empresas ya existe en una plataforma que lo hace de manera rápida y especializada, además suele ser más económico contratar una plataforma web especializada que crear una propia.

    Separador 
    #t_1_3.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 1.3  Bases de datos

    .row.align-items-center.justify-content-center.mb-4
      .col-lg-9.my-3
        .bloque-texto-d.color-secundario.p-4
          .bloque-texto-d__texto.mb-2
            i.fas.fa-quote-left
            p.text-regular Son colecciones digitales y la manera más adecuada para almacenar datos en un sistema de información, debido a sus diversas características de seguridad, capacidad de recuperación ante fallos, gestión centralizada, estandarización del lenguaje de consulta y funcionalidades avanzadas; las bases de datos son un elemento fundamental en el entorno informático, actualmente tienen una aplicación en todos los ámbitos y los campos. 
            i.fas.fa-quote-right
          .bloque-texto-d__autor 
            .h5.mb-0 - Pulido, Escobar & Núñez, 2019. 

        p(data-aos="fade-down").mt-4 Los principios y las fundamentaciones de las bases de datos se usan desde hace décadas, estas han venido evolucionando y permitiendo el avance de lo que es la informática actual.             
      .col-lg-3.my-3
        img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/21.png', alt='')  

    .row.align-items-center.justify-content-center
      .col-lg-10 
        .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/22.jpg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Aún se mantienen las bases de datos relacionales con características y métodos propios con tablas normalizadas; pero ya han aparecido otros tipos de arreglos y almacenamientos tales como bases de datos  NoSQL, dimensionales, entre otras, que permiten el desarrollo de nuevas maneras de gestionar la información, teniendo en cuenta el <b><em>big data</em></b>, los modelos analíticos y el gran volumen de datos y la diversidad que actualmente se genera.

    p(data-aos="fade-down") Las arquitecturas de uso predominantes se encuentran implementadas bajo modelos de computación en la nube, por lo que la infraestructura física y lógica de los servidores pasa a ser adquirida a través de un tercero o proveedor de servicios tecnológicos.

    p(data-aos="fade-down").mb-5 Los sistemas de gestión de bases de datos predominantes en el mercado son:

    .row.justify-content-center.align-items-center    
      .col-lg-12.up
        SlyderF.custom.mb-4(columnas="col-lg-6 col-md-4")(data-aos="fade-left")
          .tarjeta.tarjeta--slyder.bg4.p-4.h-100
            .row.justify-content-center.mb-3
              .col-8
                img.img-a.img-t.mb-3.mt-4(src="@/assets/curso/temas/23.png", alt="alt").img100.m-auto
            h4.mb-3 SQL Server	 
            p.mb-0 Del proveedor Microsoft, gestiona datos relacionales basados en el lenguaje Transact-SQL,  de gran capacidad para gestionar muchos usuarios y grandes cantidades  de datos  de  manera simultánea, con buen soporte técnico y, el costo de las licencias es medianamente alto.       
          .tarjeta.tarjeta--slyder.bg5.p-4.h-100
            .row.justify-content-center.mb-3
              .col-8
                img.img-a.img-t.mb-3.mt-4(src="@/assets/curso/temas/24.png", alt="alt").img100.m-auto
            h4.mb-3 Oracle 
            p.mb-0 Del proveedor Oracle Corporation, este tipo de base de datos cuenta con gran capacidad para gestionar muchos usuarios y grandes cantidades de datos  de  manera simultánea. Es altamente confiable, con buen soporte técnico, el costo de la licencia es relativamente alto, pero es un sistema muy estable y utilizado por grandes empresas. 

          .tarjeta.tarjeta--slyder.bg4.p-4.h-100
            .row.justify-content-center.mb-3
              .col-8
                img.img-a.img-t.mb-3.mt-4(src="@/assets/curso/temas/25.png", alt="alt").img100.m-auto
            h4.mb-3 MySQL
            p.mb-0 Es un tipo de base de datos relacional, multihilo y  multiusuario, es la base de datos más usada a nivel mundial, tiene diversas licencias (tanto comercial como no paga), las más popular es la de código abierto y uso libre; no obstante existen múltiples marcas que ofrecen MySQL promoviendo la infraestructura en la nube como Google, AWS, Oracle, entre otras.      
          .tarjeta.tarjeta--slyder.bg5.p-4.h-100
            .row.justify-content-center.mb-3
              .col-8
                img.img-a.img-t.mb-3.mt-4(src="@/assets/curso/temas/26.png", alt="alt").img100.m-auto
            h4.mb-3 PostgreSQL 
            p.mb-0 Es un tipo de base de datos relacional orientada a objetos, con licencia de código abierto y uso libre. Presenta estabilidad y capacidad de gestionar grandes volúmenes de datos.

          .tarjeta.tarjeta--slyder.bg4.p-4.h-100
            .row.justify-content-center.mb-3
              .col-8
                img.img-a.img-t.mb-3.mt-4(src="@/assets/curso/temas/27.png", alt="alt").img100.m-auto
            h4.mb-3 Cassandra
            p.mb-0 Es un tipo de base de datos NoSQL, tiene un nivel muy elevado de compatibilidad para el clúster que abarca múltiples centros de datos con la replicación asíncrona sin maestro, lo que permite operaciones de baja latencia para todos los clientes, impulsando el uso de <i>big data</i> en las empresas, además permite procesos en tiempo real con cientos de fuentes de datos diferentes. 
          .tarjeta.tarjeta--slyder.bg5.p-4.h-100
            .row.justify-content-center.mb-3
              .col-8
                img.img-a.img-t.mb-3.mt-4(src="@/assets/curso/temas/28.png", alt="alt").img100.m-auto
            h4.mb-3 Mongo DB 
            p.mb-0 Es un tipo de base de datos NoSQL, de código abierto, que en lugar de guardar los datos en tablas se orienta a documentos en estructuras de datos BSON (similar a JSON), estos esquemas hacen que la integración con aplicaciones sea más rápida. Ideal para soluciones de <i>big data.</i>

    .row.justify-content-center.align-items-center    
      .col-lg-10
        p(data-aos="fade-down").mb-5 En términos generales, todas las marcas (en especial las pagas), prometen grandes ventajas para usar sus motores de bases de datos, entre las características más importantes a la hora de seleccionar un sistema de gestión de datos son: estabilidad, prueba a fallos, capacidad de redundancia, infraestructura con alta disponibilidad, consolas administrativas, conectividad con otros sistemas de información, versatilidad en las plataformas, precios, entre otras características.  

    Separador 
    #t_1_4.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 1.4 <i>Backend</i> de autenticación 

    .cajon-b.color-acento-contenido.mb-4.py-2
      .row.align-items-center.justify-content-center
        .col-auto.my-3
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/29.png', alt='')  
        .col-10.my-3
          p(data-aos="fade-down") Este hace referencia al principio del funcionamiento de la web, donde un usuario solicita peticiones o servicios desde un navegador en un equipo de cómputo (celular, <i>desktop</i> u otro dispositivo) y estas solicitudes viajan por la red, para que un servidor envíe la respuesta a dicha petición; en la práctica esta dinámica de solicitudes y respuestas de peticiones se hacen de forma veloz, durante todo el tiempo que se usa la internet.    

    .row.justify-content-end.align-items-center.bg3.mb-5    
      .col-lg-8.my-3
        .p-4
          p(data-aos="fade-down").mb-0 Es aquí donde un usuario denominado “cliente” y un servicio provisto por un “servidor” intercambian información mediante “peticiones” y “respuestas” entre ambos, dando cuenta del funcionamiento web. Por el lado del cliente, quien está representado por las máquinas locales de los usuarios a través de navegadores, protocolos de comunicación y códigos de lenguaje fáciles de traducir por los sistemas del cliente (HTML, CSS, JSON, etc.), y por el lado del servidor que consta de elementos como la programación, la gestión de datos, los archivos y todo el funcionamiento interno de los servicios y peticiones.                          
      .col-lg-3
        img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/30.png', alt='')  

    p(data-aos="fade-down") En este sentido, para el desarrollo web existen diversos profesionales especializados, aquellos que se concentran en crear para el <i>backend</i> (del lado del servidor) y quienes se especializan en <i>frontend</i> (del lado del cliente). Algunos profesionales tienen ambas habilidades técnicas y se denominan “<i>fullstacfk</i>”.

    p(data-aos="fade-down").mb-5 En el siguiente recurso interactivo se ilustran los elementos que conforman el <i>backend</i> y el <i>frontend</i> para mejor comprensión:    

    ImagenInfograficaB.color-acento-botones.mb-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/temas/31.png', alt='')

      div(x="16%" y="30%" tooltip="ver más" numero="1") 
        .row.justify-content-center.align-items-start
          .col-auto
            img.img-a.img-t(src='@/assets/curso/temas/32.svg', alt='') 
          .col-10
            h4.mb-4 Programación en el <i>front</i>
            p.mb-0 Si bien esta parte podría parecer ambigua y quizás confusa para diferenciar entre el back y el front, es necesario mencionar que existen algunos lenguajes del lado del cliente, es decir, lenguajes que se desarrollan principalmente desde los navegadores con lógica de cliente, por lo general, hacen peticiones y conexiones con elementos del back. Entre estos lenguajes se tienen Html, Java Script, SCC.        

      div(x="16%" y="45%" tooltip="ver más" numero="2") 
        .row.justify-content-center.align-items-start
          .col-auto
            img.img-a.img-t(src='@/assets/curso/temas/33.svg', alt='') 
          .col-10
            h4.mb-4 Interfaz web
            p.mb-0 En esta se presentan y establecen todos los elementos visuales y ambientes gráficos de los recursos web.  
      div(x="16%" y="60%" tooltip="ver más" numero="3") 
        .row.justify-content-center.align-items-start
          .col-auto
            img.img-a.img-t(src='@/assets/curso/temas/34.svg', alt='') 
          .col-10
            h4.mb-4 Validaciones
            p.mb-0 En este aspecto el <i>frontend</i> se responsabiliza de cargar validaciones al momento de ingresar a zonas privadas que requieren autenticación de usuarios. Envía contraseñas y usuarios que viajan encriptadas y aceptan o no las validaciones.   
      div(x="16%" y="75%" tooltip="ver más" numero="4") 
        .row.justify-content-center.align-items-start
          .col-auto
            img.img-a.img-t(src='@/assets/curso/temas/35.svg', alt='') 
          .col-10
            h4.mb-4 Consumo de APIs
            p.mb-0 Una APIs “interfaz de programación de aplicaciones” es un mecanismo para que dos <i>software</i> se integren, puedan comunicarse y compartir recursos entre sí, por ejemplo, si se desarrolla una aplicación que tenga que ver con mapas se puede usar la API de Google Maps u otras disponibles para que usen los recursos disponibles de otros sistemas.      

      div(x="84%" y="30%" tooltip="ver más" numero="5") 
        .row.justify-content-center.align-items-start
          .col-auto
            img.img-a.img-t(src='@/assets/curso/temas/36.svg', alt='') 
          .col-10
            h4.mb-4 Programación de APIs
            p.mb-0 Programar las funcionalidades de integración para usar los recursos por otra aplicación, ya sea propia o de terceros requiere definir y programar la estructura para que pueda ser usada.  
      div(x="84%" y="45%" tooltip="ver más" numero="6") 
        .row.justify-content-center.align-items-start
          .col-auto
            img.img-a.img-t(src='@/assets/curso/temas/37.svg', alt='') 
          .col-10
            h4.mb-4 Programación en <i>backend</i>
            p.mb-0 La programación del lado del <i>backend</i> se traduce en el uso de lenguajes que se ejecutan en los servidores; lo que quiere decir que todo el trabajo del procesamiento y cálculos de datos e información se ejecutan en el servidor en el cual está alojado el servicio.    
      div(x="84%" y="60%" tooltip="ver más" numero="7") 
        .row.justify-content-center.align-items-start
          .col-auto
            img.img-a.img-t(src='@/assets/curso/temas/38.svg', alt='') 
          .col-10
            h4.mb-4 Bases de datos
            p.mb-0 Desde el cliente a través de las interfaces del <i>frontend</i> se realiza una petición, por ejemplo, una búsqueda; esta petición se realiza al servicio de base de datos (del <i>backend</i>), el proceso de búsqueda y carga de procesamiento se ejecuta en el servidor y este envía al cliente los resultados o mensajes de error en caso de presentarse.

    Separador 
    #t_1_5.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 1.5 Redundancia 
    p(data-aos="fade-down") En el marco de la Ingeniería, la Informática y la web, la redundancia se consolida como un respaldo para garantizar las mínimas caídas posibles de los servicios, de esta manera si una infraestructura o servicio falla entraría a operar el redundante; otra razón para implementar la redundancia es la conservación de la información, evitar pérdidas o incluso prevenciones contra ataques cibernéticos. 

    p(data-aos="fade-down").mb-5 Los tipos de redundancia más comunes son:         

    .row.justify-content-center
      .col-xl-4.col-md-6.col-8.mb-xl-0.mb-4(data-aos="fade-right")
        .tarjeta.tarjeta-flip.color-acento-contenido(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/temas/39.svg')})`}")
            .tarjeta-flip__contenido.p-xl-5.p-4
              .bg7.p-2.mb-4
                h4.text-center.mb-0 Redundancia de servidores
              p.mb-0 Uno de los valores agregados que ofrecen los proveedores de <i>computing cloud</i> es la de garantizar servicios redundantes, de esta manera los datos (bases de datos) y procesos (programas en línea y archivos) que estén en un proveedor falla entrarían de manera automática al respaldo, a suplir mientras el servidor principal vuelve a subir los servicios.
      .col-xl-4.col-md-6.col-8.mb-xl-0.mb-4(data-aos="flip-up")
        .tarjeta.tarjeta-flip.color-acento-contenido
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/temas/40.svg')})`}")
            .tarjeta-flip__contenido.p-xl-5.p-4
              .bg7.p-2.mb-4
                h4.text-center.mb-0 Redundancia de red
              p.mb-0 Para algunas empresas es de vital importancia mantener la conexión, por lo que algunas organizaciones deciden tener redundancia de proveedores de internet, ya sea para mantener velocidades más eficientes, separar servicios o simplemente como respaldo en caso de perder conexión con la salida principal.
      .col-xl-4.col-md-6.col-8.mb-xl-0.mb-4(data-aos="fade-left")
        .tarjeta.tarjeta-flip.color-acento-contenido
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/temas/41.svg')})`}")
            .tarjeta-flip__contenido.p-xl-5.p-4
              .bg7.p-2.mb-4
                h4.text-center.mb-0 Redundancia de poder
              p.mb-0 Algunas entidades desean asegurar que sus servicios se mantengan en línea, para este objetivo invierten en la implementación de respaldos de alimentación eléctrica, evitando cortes en caso de que la red principal falle; estos respaldos tienen múltiples arquitecturas y es un tema que debe consultarse con expertos en ingeniería eléctrica, sistemas de protección y redundancia de energía.

</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    indicadorTarjetaFlip: true,
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
