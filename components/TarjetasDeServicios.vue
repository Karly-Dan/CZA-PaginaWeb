<template>
    <div class="contenedor">
        <div class="item1">
            <h1>Servicios Contables <br> <br></h1>
            <img src="../assets/iconos/contabilidad.png" alt="" class="img2">
        </div>
        <div class="item2">
            <h1>Asesoría Fisacal y Legal</h1>
            <img src="../assets/iconos/operador.png" alt="" class="img2">
        </div>
        <div class="item3">
            <h1>Ingeniería Administrativa</h1>
            <img src="../assets/iconos/administrador.png" alt="" class="img2">
        </div>
        <div class="item4">
            <h1>Facturación Electrónica</h1>
            <img src="../assets/iconos/electronica.png" alt="" class="img2">
        </div>
        <div class="item5">
            <h1>tecnologías de la Infromación</h1>
            <img src="../assets/iconos/informacion.png" alt="" class="img2">
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
        background-size: 544px;
        margin-bottom: 20px;
    }
    .item2 {
        background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(../assets/img/financiero.jpg);
        background-repeat: no-repeat;
        width: 100%;
        background-size: 470px;
        margin-bottom: 20px;
    }
    .item3 {
        background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(../assets/img/administrativa.jpg);
        background-repeat: no-repeat;
        width: 100%;
        background-size: 470px;
        margin-bottom: 20px;
    }
    .item4 {
        background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(../assets/img/electronica.jpg);
        background-repeat: no-repeat;
        width: 100%;
        background-size: 470px;
        margin-bottom: 20px;
    }
    .item5 {
        background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(../assets/img/informacion.jpg);
        background-repeat: no-repeat;
        width: 100%;
        background-size: 470px;
        margin-bottom: 20px;
    }

    @media (min-width: 390px){
        .item1, .item2, .item3, .item4, .item5 {
            width: 90%;
        }
    }
    @media (min-width: 557px){
        .item1, .item2, .item3, .item4, .item5{
            width: 49%;
        }
    }
    @media (min-width: 1000px){
    .item1, .item2, .item3, .item4, .item5 {
        width: 26%;
        }
    }
    .img2 {
        height: 148px;
        margin: auto;
        display: block;
        padding-top: 100px;
        filter: invert(99%) sepia(0%) saturate(1136%) hue-rotate(286deg) brightness(116%) contrast(100%);
        opacity: 0.55;
        margin-top: -76px;
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