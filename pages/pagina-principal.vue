<template>
  <main>
    <header-base />
    <section class="section">
        <img src="../assets/img/grupo.jpg" alt="" class="img1">
        <div class="div2"></div>
    </section>
    <section class="tarjetas-vue">
        <h1 class="titulo-de-tarjetas">Asesoramos a las organizaciones en estrategias de creación de valor</h1>
        <div>
            <tarjetas-vue />
        </div>
    </section>
    <br>
    <section class="section2">
        <h1 class="titulos">Planifique su exito ahora</h1>
        <p class="subtitulo">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nesciunt dolore facilis magni ipsam sapiente culpa nostrum fugiat veritatis, sunt adipisci rerum optio placeat quas. Perferendis harum quos neque cupiditate ipsam?</p>
        <boton />
    </section>
    <section class="tarjetas-servicios">
        <h1 class="titulos">Que servicios ofrecemos</h1>
        <p class="subtitulo">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint Ocecat cupidatat non proident, sunt in culpa</p>
        <tarjetas-de-servicios />
    </section>
    <section class="personal">
        <h1 class="titulo-personal">Integrantes del quipo</h1>
        <p class="subtitulo-personal">Somos socios expertos comprometidos</p>
        <p class="subtitulo">Valoramos enormemente las relaciones sólidas y hemos visto los beneficios que aportan a nuestro negocio. Los comentarios de los clientes son vitales para ayudarnos a hacerlo bien.</p>
        <tarjetas-del-personal />
    </section>
    <section class="sellos">
        <h1 class="titulo-sello">Socios de información</h1>
        <p class="subtitulo">Sample text. Click to select the text box. Click again or double click to start editing the text.</p>
        <div class="img-sellos">
        <img src="../assets/img/firma.png" alt="" class="sellos-img">
        <img src="../assets/img/firma.png" alt="" class="sellos-img">
        <img src="../assets/img/firma.png" alt="" class="sellos-img">
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
        height: 350px;
        background-color: #f74a0c;
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
            margin-top: -31px;
        }
        .titulo-de-tarjetas {
            margin-left: auto;
            margin-right: auto;
            padding-top: 40px;
        }
        .sellos-img {
            max-width: 100%;
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
            margin-top: -404px;
        }
    }
.titulo-de-tarjetas {
    color: #111111;
    height: 250px;
    font-size: 1.5rem;
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
    font-size: 1.5rem;
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
    padding-left: 50px;
    padding-right: 50px;
    text-align: center;
    font-size: 1rem;
    line-height: 1.6;
    color: #111111;
}
.tarjetas-servicios {
    margin-left: 10px;
    margin-right: 10px;
}
.personal {
    background-color: white;
    text-align: center;
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
    font-size: 1.5rem;
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
    display: flex;
    justify-content: space-around;
    margin-top: 80px;
    flex-wrap: wrap;
    width: 100%;
}
.titulo-sello {
    color: #111111;
    font-size: 1.5rem;
    line-height: 1.1;
    text-align: center;
    font-family: Montserrat,sans-serif;
    font-weight: 400;
    margin-left: auto;
    margin-right: auto;
    text-transform: none;
}
</style>