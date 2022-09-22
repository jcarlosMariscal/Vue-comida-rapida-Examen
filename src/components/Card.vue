<template>
  <!-- <grid> -->
  <div class="allCard">
    <div class="card" style="width: 18rem">
      <imagen>
        <img class="card-img-top img-fluid" v-bind:src="url" :alt="nombre" />
      </imagen>
      <div class="card-body">
        <h5 class="card-title">{{ nombre }}</h5>
        <p class="card-text">
          {{ descripcion }}
        </p>
      </div>
      <ul class="list-group list-group-flush">
        <li class="list-group-item">{{ costo }}</li>
      </ul>
      <!-- <div class="card-body">
          <a href="#" class="card-link">Card link</a>
          <a href="#" class="card-link">Another link</a>
        </div> -->
    </div>
  </div>
  <!-- </grid> -->
</template>
<script>
import Imagen from "./Imagen.vue";
export default {
  props: {
    url: {
      String,
    },
    nombre: {
      String,
    },
    descripcion: {
      String,
    },
    costo: {
      String,
    },
  },
  components: { Imagen },
};
</script>
<style scoped>
.allCard {
  display: inline-block;
  text-align: center;
  border: 1px solid #f2f2f2;
  padding: 1%;
  border-radius: 5px;
  margin: 4px;
}
a {
  text-decoration: none;
  color: snow;
  background-color: #301675;
  padding: 0.5rem;
  border-radius: 5px;
  border: 1px solid #f2f2f2;
}
</style>
