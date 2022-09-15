<template>
  <section class="contenedor">
        <div class="titulo-de-tarjeta">
          <img src="../assets/img/bombilla.png" alt="">
          <h1>ESTRATEGIA</h1>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi voluptatibus, odit nulla eaque placeat facilis, deleniti non amet tempore, autem totam perspiciatis aperiam quam sunt! Accusamus libero tempore delectus debitis.</p>
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
        padding: 20px;
        height: 400px;
    }
    .titulo-de-tarjeta {
      box-shadow: 5px 5px 0px 0 rgba(0,0,0,0.2);
      width: 100%;
      text-align: center;
      font-family: Montserrat, sans-serif !important;
      color: #555c66 !important;
      font-style: italic;
      height: auto;
      width: 300px;
      margin-right: 25px;
      margin-left: 25px;
      margin-bottom: 85px;
      background-color: white;
      height: auto;
      font-size: 1.25rem;
      padding: 20px;
    }
    img {
    height: 42px;
    width: 42px;
    border-radius: 50%;
    background-color: rgb(224, 229, 235) !important;
    margin-top: 20px;
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
    }
    @media (min-width: 600px){
        .personal {
            width: 50%;
        }
    }
  @media (min-width: 1000px){
    .personal {
        width: 32%;
    }
  }
</style>