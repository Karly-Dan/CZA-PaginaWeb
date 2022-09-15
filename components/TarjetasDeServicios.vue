<template>
    <div class="contenedor">
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
        height: 300px;
    }
    .item1 {
        background-image: url(../assets/img/dinero.webp);
        background-repeat: no-repeat;
        width: 100%;
    }
    @media (min-width: 390px){
        .item1 {
            width: 100%;
        }
    }
    @media (min-width: 600px){
        .item1 {
            width: 60%;
        }
    }
    @media (min-width: 1000px){
    .item1 {
        width: 40%;
        }
    }
    .img2 {
        height: 111px;
        margin: auto;
        display: block;
        padding-top: 100px;
        filter: invert(99%) sepia(0%) saturate(1136%) hue-rotate(286deg) brightness(116%) contrast(100%);
        opacity: 0.55;
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