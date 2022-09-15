<template>
    <div>
        <div>
            <header1></header1>
        </div>
        <section class="contenedor-tarjetasvue">
            <br>
            <tarjetas-vue></tarjetas-vue>
        </section>
        <br>
        <section>
            <br>
            <boton-vue></boton-vue>
        </section>
        <br>
        <section>
            <tarjetas-del-personal></tarjetas-del-personal>
            <tarjetas-de-servicios-vue></tarjetas-de-servicios-vue>
        </section>
        <br>
        <div>
            <Footer></Footer>
        </div>


    </div>
</template>

<script>
    import TarjetasVue from '../components/Tarjetas.vue';
    import BotonVue from '../components/Boton.vue';
    import Footer from '../components/Footer.vue'
    import Header1 from '../components/Header.vue'
    import TarjetasDelPersonal from '../components/TarjetasDelPersonal.vue';
    import TarjetasDeServiciosVue from '../components/TarjetasDeServicios.vue';

export default {
    components: {
    TarjetasVue,
    BotonVue,
    Footer,
    Header1,
    TarjetasDelPersonal,
    TarjetasDeServiciosVue,
}
}
</script>

<style>
    body {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
    }
</style>