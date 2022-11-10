<template>
    <main>
      <header-base/>
      <section class="section">
          <img src="../assets/img/grupo.jpg" alt="" class="img1">
          <div class="div2"></div>
          <div class="slider">
            <ul>
                <li>
                    <h2 class="titulo-carrusel">Misión</h2>
                    <p class="subtitulo-carrusel">Ofrecer soluciones tecnológicas inteligentes acordes a las necesidades de nuestros clientes, que le permitan eficientar sus procesos productivos, generando utilidades a menor costo.</p>
                </li>
                <li> 
                    <h2 class="titulo-carrusel">Visión</h2>
                    <p class="subtitulo-carrusel">Adaptarnos a las nuevas tecnologías para brindar seguridad a nuestros clientes, de la infromación que se genera, derivada de su actividad comercial.</p>
                </li>
                <li>
                    <h2 class="titulo-carrusel">Valores</h2>
                    <p class="subtitulo-carrusel">TRANSPARENCIA
                    <br>
                    HONESTIDAD
                    <br>   
                    CONFIANZA
                    <br>
                    INTEGRIDAD
                    <br>
                    PASIÓN
                    <br>
                    RESPONSABILIDAD
                    <br>
                    TRANSFORMACIÓN
                    <br>
                </p>
                </li>
            </ul>
          </div>
      </section>
      <section class="tarjetas-vue">
          <h1 class="titulo-de-tarjetas">Comparativos, Diagnóstico, Presupuesto y Disponibilidad.</h1>
          <div>
              <tarjetas-vue />
          </div>
      </section>
      <br>
      <section class="section2">
          <h1 class="titulos">Facturación Electrónica</h1>
          <p class="subtitulo">PAC autorizado por el SAT, ofreciendo seguridad garantizada y facturas las 24 horas
        Accesible desde cualquier dispositivo con internet  
        Personalización de los comprobantes en PDF, con diseño color y logotipo. Capacidad para operar con múltiples sucursales y usuarios.   </p>
          <boton />
      </section>
      <section style="display: contents;">
          <div class="content" style=" background-color: white; padding-bottom: 40px; padding-top: 20px;">
              <h2 class="subtitulo-personal" >Soluciones Inteligentes</h2>
              <p style="line-height: 1.4; font-style: italic; font-weight: 400; font-family: 'Open Sans',sans-serif !important; color: #808080 !important;">A TRAVÉS DE TECNOLOGÍAS DE LA INFORMACIÓN</p>
              <li style="font-size: 1.125rem; font-family: 'Open Sans',sans-serif; margin-bottom: 8px;">ATENCIÓN PERSONALIZADA</li>
              <li style="font-size: 1.125rem; font-family: 'Open Sans',sans-serif; margin-bottom: 8px;">COMPARATIVOS DE INGRESOS Y EGRESOS</li>
              <li style="font-size: 1.125rem; font-family: 'Open Sans',sans-serif; margin-bottom: 8px;">DIAGNÓSTICO FINANCIERO</li>
              <li style="font-size: 1.125rem; font-family: 'Open Sans',sans-serif; margin-bottom: 8px;">PRESUPUESTO</li>
              <li style="font-size: 1.125rem; font-family: 'Open Sans',sans-serif; margin-bottom: 8px;">INFORMACIÓN DISPONIBLE 365 DÍAS DEL AÑO </li>
              <boton />
          </div>
          <div style="background-color:white; padding-bottom: 20px;">
              <img src="../assets/img/business-people-shaking-hands-together.jpg" alt="" style="width: 90%; height: auto; display: block; margin: auto; ">
          </div>
      </section>
      <section class="tarjetas-servicios">
          <h1 class="titulos">Que servicios ofrecemos</h1>
          <p class="subtitulo">Consultoría para negocios enfocados en el manejo y administración de sus finanzas. Especializados En El Área Legal, Contable, Fiscal, Facturación Electrónica Y Administrativa</p>
          <tarjetas-de-servicios />
      </section>
      <section class="personal">
          <h1 class="titulo-personal">Integrantes del quipo</h1>
          <p class="subtitulo-personal">Somos socios expertos comprometidos</p>
          <p class="subtitulo">Valoramos enormemente las relaciones sólidas y hemos visto los beneficios que aportan a nuestro negocio. </p>
          <tarjetas-del-personal />
      </section>
      <section class="acerca-de-la-compañia">
          <div class="div-copañia">
              <h2 class="titulo-compañia">ANÁLISIS, MEJORA Y RESULTADOS</h2>
              <p class="subtitulo-compañia">Ingeniería Administrativa</p>
              <p class="parrafo-compañia">Ofrecemos acciones que se encaminan a optimizar sus procesos internos, manejo, acceso y seguridad de la información de su organización, ya sea en su red local o desde cualquier punto que tenga acceso a ella.</p>
              <boton />
          </div>
          <div class="contenedor-img">
              <img src="../assets/img/business-brainstorming-graph-chart-report-data-concept.jpg" alt="" class="img-compañia">
          </div>
      </section>
      <section class="sellos">
          <div>
          <h1 class="titulo-sello">Centro de Profesionalización de Capital Humano.</h1>
          <p class="subtitulo">Certificadores oficiales</p>
          </div>
          <div class="img-sellos">
          <img src="../assets/img/sello.jpeg" alt="" class="sellos-img">
          </div>
      </section>
      <Footer></Footer>
    </main>
  </template>
  
  <script>
      import HeaderBase from '../components/Header.vue';
      import TarjetasVue from '../components/Tarjetas.vue';
      import TarjetasDeServicios from '../components/TarjetasDeServicios.vue';
      import Boton from '../components/Boton.vue';
      import TarjetasDelPersonal from '../components/TarjetasDelPersonal.vue';
  export default {
      components: {
      HeaderBase,
      TarjetasVue,
      TarjetasDeServicios,
      Boton,
      TarjetasDelPersonal
  }
  }
  </script>
  
  <style>
      body {
          box-sizing: border-box;
          margin: 0;
          padding: 0;
          overflow-x: hidden;
          background-color:  #e0e5eb;
      }
      .section {
          background-color:  #e0e5eb;
      }
      .section2 {
          text-align: center;
          margin-bottom: 40px;
      }
      .section, h2 {
          font-size: 1.875rem;
          line-height: 1.1;
          text-transform: none;
          font-family: Montserrat,sans-serif;
          font-weight: 400;
          padding-bottom: 20px;
      }
      .div2 {
          height: 400px;
          background-color: #00467a;
          margin-top: -120px;
          
      }
      @media (min-width: 300px) {
          .section .img1 {
              width: 323px;
              height: 230px;
              display: block;
              object-fit: cover;
              margin-left: auto;
              margin-right: auto;
          }
          .div2 {
              margin-top: -59px;
          }
          .titulo-de-tarjetas {
              margin-left: auto;
              margin-right: auto;
              padding-top: 40px;
              width: 340px;
          }
          .sellos-img {
              max-width: 100%;
          }
          .subtitulo {
              width: 340px;
          }
          .titulos {
              font-size: 1.875rem;
          }
          .subtitulo-personal {
              font-size: 1.5rem;
          }
          .img-compañia {
              height: 250px;
              display: block;
              margin: auto;
          }
          .content {
              padding-left: 20px;
              padding-right: 20px;
          }
          .img-sellos {
            display: grid;
          }
          .silder {
            width: -moz-available;
            margin-right: 12px;
          }
          
      }
      @media (min-width: 700px) {
          .section .img1 {
              width: 495px;
              height: 330px;
              display: block;
              object-fit: cover;
              margin-left: auto;
              margin-right: auto;
          }
          .div2 {
              margin-top: -113px;
          }
          .titulo-de-tarjetas {
              width: 700px;
              font-size: 3rem;
              line-height: 1.1;
          }
          .subtitulo {
              width: 630px;
          }
          .acerca-de-la-compañia {
              display: flex;
          }
          .div-copañia {
              background-color: white;
              padding-left: 150px;
              padding-left: 34px;
              padding-right: 55px;
              text-align: left;
          }
          .titulo-compañia {
              width: 202px;
          }
          .subtitulo-compañia {
              font-family: Montserrat, sans-serif;
              background-image: none;
              letter-spacing: normal;
              text-transform: none;
              font-weight: 400;
              font-size: 3rem;
              line-height: 1.1;
          }
          .parrafo-compañia {
              color: #555c66 !important;
              font-size: 1.125rem;
              line-height: 2
          }
          .img-compañia {
              height: 261px;
          }
          .content {
              padding-left: 40px;
              padding-right: 40px;
          }
          .img-sellos {
            display: flex;
          }
      }
      @media (min-width: 991px){
          .section .img1 {
              width: 634px;
              height: 453px;
              display: block;
              object-fit: cover;
              margin-left: auto;
              margin-right: auto;
          }
          .div2 {
              margin-top: -31px;
          }
          .titulo-de-tarjetas {
              width: 780px;
          }
          .acerca-de-la-compañia {
              display: flex;
          }
          .div-copañia {
              background-color: white;
              padding-left: 65px;
          }
          .subtitulo-compañia {
              font-family: Montserrat, sans-serif;
              background-image: none;
              letter-spacing: normal;
              text-transform: none;
              font-weight: 400;
              font-size: 3rem;
              line-height: 1.1;
          }
          .parrafo-compañia {
              color: #555c66 !important;
              font-size: 1.125rem;
              line-height: 2
          }
          .content {
              padding-right: 500px;
          }
          .img-sellos {
            display: flex;
          }
          .img-compañia {
            height: 480px;
          }
          
      }
      @media (min-width: 1199px){
          .section .img1 {
              width: 970px;
              height: 710px;
              display: block;
              object-fit: cover;
              margin-left: auto;
              margin-right: auto;
          }
          .div2 {
              margin-top: -372px;
          }
          .titulos, .titulo-de-tarjetas, .titulo-sello, .subtitulo-personal, .subtitulo-compañia{
              font-weight: 400;
              font-size: 3rem;
          }
          .subtitulo {
              font-size: 1.25rem;
          }
          .titulo-de-tarjetas {
              width: 822px;
          }
          .acerca-de-la-compañia {
              display: flex;
          }
          .div-copañia {
              background-color: white;
              padding-left: 150px;
          }
          
          .content {
              padding-right: 600px;
          }
          .img-sellos {
            display: flex;
          }
      }
        .titulo-de-tarjetas {
            color: #111111;
            height: 250px;
            line-height: 1.1;
            text-align: center;
            font-family: Montserrat,sans-serif;
            font-weight: 400;
            margin-left: auto;
            margin-right: auto;
            text-transform: none;
            background-color:  #e0e5eb;
        }
        .titulos {
            color: #111111;
            line-height: 1.1;
            text-align: center;
            font-family: Montserrat,sans-serif;
            font-weight: 400;
            margin-left: auto;
            margin-right: auto;
            text-transform: none;
            background-color:  #e0e5eb;
        }
        .subtitulo {
            text-align: center;
            line-height: 1.6;
            color: #111111;
            margin: 30px auto 0;
            margin-bottom: 20px;
        }
        .tarjetas-servicios {
            margin-left: 10px;
            margin-right: 10px;
        }
        .personal {
            background-color: white;
            text-align: center;
            padding-bottom: 20px;
        }
        .titulo-personal {
            text-transform: uppercase;
            letter-spacing: 6px;
            color: #555c66;
            font-size: 1.25rem;
            line-height: 1.2;
            font-weight: 400;
            font-family: 'PT Sans',sans-serif;
            margin-top: 20px;
            padding-top: 40px;
        }
        .subtitulo-personal {
            font-family: Montserrat,sans-serif;
            color: #111111;
            font-weight: 400;
            line-height: 1.1;
        }
        p {
            font-size: 1.25rem;
            font-family: 'Open Sans',sans-serif;
            line-height: 1.6;
        }
        .sellos{
            text-align: center;
            background-color: white;
            margin: 0;
            padding: 20px;
        }
        .img-sellos {
            width: 100%;
        }
        .sellos-img {
            margin:auto;
            padding-bottom: 30px;
            padding-top: 30px;
            height: 275px;
        }
        .titulo-sello {
            color: #111111;
            line-height: 1.1;
            text-align: center;
            font-family: Montserrat,sans-serif;
            font-weight: 400;
            margin-left: auto;
            margin-right: auto;
            text-transform: none;
        }
        .div-copañia {
            background-color: white;
            padding: 35px;
        }
        .titulo-compañia {
            margin-top: 0;
            text-transform: uppercase;
            letter-spacing: 6px;
            color: #555c66;
            font-size: 1.25rem;
            line-height: 1.2;
            font-weight: 400;
            font-family: 'PT Sans',sans-serif;
        }
        .subtitulo-compañia {
            font-family: Montserrat,sans-serif;
            color: #111111;
            font-weight: 400;
            line-height: 1.1;
            margin: 0px;
            font-size: 1.5rem;
        }
        
        @keyframes cambio {
            0% {margin-left: 0;}
            20% {margin-left: 0;}

            25% {margin-left: -100%;}
            45% {margin-left: -100%;}

            50%{margin-left: -100%;}
            70%{margin-left: -100%;}
            
            75%{margin-left: -200%;}
            100%{margin-left: -200%;}
        }
        
        .slider {
            width: 355px;
            overflow: hidden;
            margin-top: -380px;
            background-color: white;
            position: absolute;
            height: 350px;
            margin-left: 12px;
        }
        .slider ul {
            display: flex;
            animation: cambio 15s infinite
            alternate linear;
            width: 400%;
            padding-left: 0;
        }
        .slider li {
            width: 25%;
            list-style: none;
        }
        .titulo-carrusel {
            font-size: 1.25rem;
            text-transform: uppercase;
            font-weight: 400;
            font-family: Montserrat, sans-serif !important;
            color: #df612a;
            padding-left: 20px;
        }
        .subtitulo-carrusel {
            font-size: 1.125rem;
            font-family: 'Open Sans',sans-serif;
            padding-left: 20px;
            padding-right: 5px;
        }
        .contenedor-img {
            background-color: white;
            display: flex;
        }
  </style>