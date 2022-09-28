<template>
    <div class="contenedor">
        <div class="item1">
            <h1>Servicios Contables</h1>
            <img src="../assets/img/signo-de-dolar.png" alt="" class="img2">
        </div>
        <div class="item1">
            <h1>Servicios Contables</h1>
            <img src="../assets/img/signo-de-dolar.png" alt="" class="img2">
        </div>
        <div class="item1">
            <h1>Servicios Contables</h1>
            <img src="../assets/img/signo-de-dolar.png" alt="" class="img2">
        </div>
        <div class="item1">
            <h1>Servicios Contables</h1>
            <img src="../assets/img/signo-de-dolar.png" alt="" class="img2">
        </div>
        <div class="item1">
            <h1>Servicios Contables</h1>
            <img src="../assets/img/signo-de-dolar.png" alt="" class="img2">
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
    .contenedor {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-around;
    }
    .item1 {
        background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(../assets/img/DINERO.jpg);
        background-repeat: no-repeat;
        width: 100%;
        background-size: 470px;
        margin-bottom: 20px;
    }
    @media (min-width: 390px){
        .item1 {
            width: 90%;
            background-size: 465px;
        }
    }
    @media (min-width: 557px){
        .item1 {
            width: 49%;
        }
    }
    @media (min-width: 1000px){
    .item1 {
        width: 26%;
        }
    }
    .img2 {
        height: 111px;
        margin: auto;
        display: block;
        padding-top: 100px;
        filter: invert(99%) sepia(0%) saturate(1136%) hue-rotate(286deg) brightness(116%) contrast(100%);
        opacity: 0.55;
        margin-top: -45px;
        padding-bottom: 9px;
    }
    h1 {
        text-align: center;
        font-size: 1.5rem;
        text-transform: uppercase;
        letter-spacing: 3px;
        font-family: Montserrat,sans-serif;
        color: #ffffff;
    }
</style>