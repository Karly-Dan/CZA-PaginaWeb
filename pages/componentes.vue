<template>
    <div>
        <section class="contenedor-tarjetas">
            <br>
            <tarjetas-vue></tarjetas-vue>
            <br>
            <br>
        </section>
        <section>
            <br>
            <boton-vue></boton-vue>
            <br>
        </section>


    </div>
</template>

<script>
    import tarjetasVue from '/components/Tarjetas.vue';
    import BotonVue from '/components/Boton.vue';

export default {
    components: {
        tarjetasVue,
        BotonVue,
    }
}
</script>

<style>
    .contenedor-tarjetas {
        background-color: #df612a;
    }
    body {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
    }
</style>