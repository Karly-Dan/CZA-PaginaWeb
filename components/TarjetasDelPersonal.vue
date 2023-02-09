<template>
  <div class="contenedor-principal">
        <div class="personal">
            <img src="../assets/img/personal.jpg" alt="">
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Temporibus laudantium tempore minus cumque molestias assumenda, quas quos eaque rerum odio pariatur totam, corrupti laboriosam ad unde quam officia. Distinctio, ullam.</p>
            <h1>Conde Zarate</h1>
        </div>
        <div class="personal">
            <img src="../assets/img/personal.jpg" alt="">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Error unde fugit quia vero veniam laborum minus eius voluptatibus ut, laudantium tempore, placeat, qui commodi? Dolor voluptatem incidunt laborum sint voluptate?</p>
            <h1>Conde Zarate</h1>
        </div>
        <div class="personal">
            <img src="../assets/img/personal.jpg" alt="">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores totam ad quod voluptate consequatur et laudantium reiciendis ipsum quisquam! Debitis velit dignissimos vel, accusantium ipsa quis! A est iusto rerum!</p>
            <h1>Conde Zarate</h1>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
  .contenedor-principal {
        display: flex;
        flex-wrap: wrap;
    }
    .personal {
        width: 100%;
        text-align: center;
        line-height: 1.6;
        color: #808080 !important;
        font-family: 'Open Sans',sans-serif;

    }
    @media (min-width: 600px) {
        .personal {
            width: 50%;
        }
  }
  @media (min-width: 1000px) {
    .personal {
        width: 32%;
    }
}
img {
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 50%;
    border-radius: 50% ;
    border-color: #00467a;
    border-width: 9px;
    border-style: double;
    background-size: cover;
}
h1 {
    color: #111111;
}
p {
  padding: 25px;
}

</style>