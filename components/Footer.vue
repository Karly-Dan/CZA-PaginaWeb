<template>
    <div>
        <div class="contenedor">
            <div style="margin-bottom: 35px;">
                <p  style="margin-top: 0; padding-top: 20px;"><img src="../assets/iconos/gmail.png" alt="">contacto@condezarate.mx</p>
                <p><img src="../assets/iconos/llamada-telefonica.png" alt="">55 1254 3594</p>
            </div>
            <div> 
                <p>Síguenos en Redes</p>
                <a href="https://www.instagram.com/condezarateyasociados/?hl=es" target="_blank" rel="noopener noreferrer"><img src="../assets/iconos/instagram.png" alt=""></a>
                <a href="https://www.facebook.com/people/Conde-Zarate-Asociados-SC/100057309015417/" target="_blank" rel="noopener noreferrer"><img src="../assets/iconos/facebook.png" alt=""></a>
                <a href="https://www.youtube.com/@condezarateasociados3097" target="_blank" rel="noopener noreferrer"><img src="../assets/iconos/youtube.png" alt=""></a>
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
    img {
        margin-right: 5px;
        margin-bottom: -5px;
    }
    @media (min-width: 300px){
        .contenedor {
            display: block;
            text-align: center;
            height: 225px;
            justify-content: space-evenly;
        }
    }
    @media (min-width: 700px) {
        .contenedor {
            display: flex;
            height: 160px;
        }
    }
</style>
