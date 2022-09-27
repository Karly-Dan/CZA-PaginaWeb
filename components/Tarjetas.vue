<template>
  <section class="contenedor">
        <div class="titulo-de-tarjeta">
          <img src="../assets/img/bombilla.png" alt="">
          <h1>ESTRATEGIA</h1>
          <p>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur</p>
        </div>
        <div class="titulo-de-tarjeta2">
          <img src="../assets/img/bombilla.png" alt="">
          <h1>ESTRATEGIA</h1>
          <p>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur</p>
        </div>
        <div class="titulo-de-tarjeta3">
          <img src="../assets/img/bombilla.png" alt="">
          <h1>ESTRATEGIA</h1>
          <p>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur</p>
        </div>
    </section>

</template>

<script>
export default {

}
</script>

<style scoped>
    .contenedor {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        background-color: orangered;
    }
    .titulo-de-tarjeta, .titulo-de-tarjeta2, .titulo-de-tarjeta3 {
      box-shadow: 5px 5px 0px 0 rgba(0,0,0,0.2);
      width: 100%;
      text-align: center;
      font-family: Montserrat, sans-serif !important;
      color: #555c66 !important;
      font-style: italic;
      margin-right: 25px;
      margin-left: 25px;
      background-color: white;
      font-size: 1.25rem;
      padding: 30px;
    }
    img {
    height: 42px;
    width: 42px;
    border-radius: 50%;
    background-color: rgb(224, 229, 235) !important;
    padding: 18px;
    }
    p {
      font-style: italic;
      font-family: 'Open Sans',sans-serif;
      margin: 20px 9px 0;
    }
    h1 {
      letter-spacing: 2px;
      font-size: 1.25rem;
      font-weight: 400;
      text-transform: uppercase;
      color: #555c66 !important;
    }
@media (min-width: 300px) {
    .contenedor{
      height: 945px;
    }
    .titulo-de-tarjeta, .titulo-de-tarjeta2, .titulo-de-tarjeta3 {
      width: 300px;
      height: 256px
    }
    .titulo-de-tarjeta {
      margin-top: -115px;
    }
}
@media (min-width: 700px) {
    .contenedor {
      height: 1165px;
    }
    .titulo-de-tarjeta, .titulo-de-tarjeta2, .titulo-de-tarjeta3 {
      width: 478px;
    }
}
@media (min-width: 991px){
    .contenedor {
      height: 800px;
    }
    .titulo-de-tarjeta {
      width: 335px;
      margin-top: -50px;
      margin-bottom: 134px;
    }
    .titulo-de-tarjeta2 {
      width: 335px;
      margin-bottom: 208px;
      margin-top: -115px;
    }
    .titulo-de-tarjeta3 {
      width: 335px;
    }
}
@media (min-width: 1199px){
    .contenedor{
      height: 400px;
    }
    .titulo-de-tarjeta, .titulo-de-tarjeta2, .titulo-de-tarjeta3  {
      width: 234px;
      height: 291px;
    }
}
</style>