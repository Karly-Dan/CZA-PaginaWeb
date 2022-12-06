<template>
    <div>
        <h1>Contáctanos</h1>
        <div class="contenedor">
            <div style="margin-bottom: 35px;">
                <img src="../assets/img/correo.png" alt="">
                <p style="margin-top:0;">contacto@condezarate.mx</p>
            </div>
            <div> 
                <img src="../assets/img/telefono.png" alt="">
                <p style="margin-top:0;">55 6285 7771</p>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
    div {
        background-color: #00467a;
        color: white;
        font-style: italic;
    }
    h1 {
        margin-bottom: 35px;
        text-align: center;
        margin-top: 0;
        padding-top: 20px;
    }
    @media (min-width: 300px){
        .contenedor {
            display: block;
            text-align: center;
            height: 174px;
            justify-content: space-evenly;
        }
    }
    @media (min-width: 700px) {
        .contenedor {
            display: flex;
            height: 118px;
        }
    }
</style>
