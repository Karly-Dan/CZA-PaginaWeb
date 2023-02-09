<template>
  <section class="contenedor">
        <div class="titulo-de-tarjeta">
          <img src="../assets/iconos/reloj-de-arena.png" alt="">
          <h1>DECLARACIONES</h1>
          <p>Entrega de declaraciones provisionales, definitivas e informativas en fiempo y forma a la autoridad, que permitan que el contribuyente este al día en su cumplimiento de obligaciones.</p>
        </div>
        <div class="titulo-de-tarjeta2">
          <img src="../assets/iconos/advertencia.png" alt="">
          <h1>EVITAR GASTOS</h1>
          <p>Revisión permanente de sus operaciones para que no generen gastos por actualizaciones, recargos, multas y gastos de ejecución de los impuestos u otras obligaciones establecidas en la Ley, por ejemplo: EFOS o EDOS.</p>
        </div>
        <div class="titulo-de-tarjeta3">
          <img src="../assets/iconos/martillo-legal.png" alt="">
          <h1>CUMPLIMIENTO</h1>
          <p>Actualización de libros de actas de asambleas ordinarias y/o extraordina-rias. emisión de acciones o partes sociales, así como los avisos de privacidad exigidos por la ley, contratos de
confidencialidad, etc.</p>
        </div>
        <div class="titulo-de-tarjeta4">
          <img src="../assets/iconos/ley.png" alt="">
          <h1>DEFENSA</h1>
          <p>Defensa en las Instancias correspondientes en materia fiscal: por determinación de créditos fiscales, bloqueo de sellos digitales, incorporación a la lista
de EFOS o EDOS, etc.</p>
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
        background-color: #00467a;
    }
    .titulo-de-tarjeta, .titulo-de-tarjeta2, .titulo-de-tarjeta3, .titulo-de-tarjeta4 {
      box-shadow: 5px 5px 0px 0 rgba(32, 31, 31, 0.51);
      width: 100%;
      text-align: center;
      font-family: sans-serif !important;
      color: #555c66 !important;
      font-style: italic;
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
    border-style: double;
    }
    p {
      font-style: italic;
      font-family: 'Open Sans',sans-serif;
      margin: 20px 9px 0;
      font-size: 1rem;
      line-height: 1.6;
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
      height: 1550px;
    }
    .titulo-de-tarjeta, .titulo-de-tarjeta2, .titulo-de-tarjeta3, .titulo-de-tarjeta4{
      width: 250px;
      height: 345px;
      margin-bottom: 20px;
    }
    .titulo-de-tarjeta {
      margin-top: -65px;
    }
}
@media (min-width: 700px) {
    .contenedor {
      height: 1564px;

    }
    .titulo-de-tarjeta, .titulo-de-tarjeta2, .titulo-de-tarjeta3, .titulo-de-tarjeta4 {
      width: 478px;
    }
}
@media (min-width: 991px){
    .contenedor {
      height: 850px;
      margin-top: 100px;
    }
    .titulo-de-tarjeta {
      width: 300px;
      margin-top: -50px;
      margin-bottom: 134px;
      margin-right: 50px;
    }
    .titulo-de-tarjeta2 {
      width: 300px;
      margin-bottom: 208px;
      margin-top: -115px;
    }
    .titulo-de-tarjeta3 {
      width: 300px;
      margin-top: -70px;
      margin-right: 50px;

    }
    .titulo-de-tarjeta4 {
      width: 300px;
      margin-top: -95px;
    }
}
@media (min-width: 1199px){
    .contenedor {
      height: 450px;
    }
    .titulo-de-tarjeta, .titulo-de-tarjeta2, .titulo-de-tarjeta3, .titulo-de-tarjeta4 {
      width: 200px;
      height: 404px;
      margin-right: 35px;
    }
    .titulo-de-tarjeta3 {
      margin-top: -55px;
    }
    .titulo-de-tarjeta4 {
      margin-top: -115px;
    }
    .titulo-de-tarjeta {
      margin-left: 20px;
    }
}
</style>