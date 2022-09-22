<template>
  <grid>
    <div class="card" style="width: 18rem">
      <img class="card-img-top img-fluid" v-bind:src="url" :alt="nombre" />
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
  </grid>
</template>
<script>
import Grid from "./Grid.vue";
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
  components: { Grid },
};
</script>
<style scoped>
img {
  /* width: 4rem; */
  widows: 100%;
  height: 150px;
  /* height: 2rem; */
  /* padding: 4rem; */
  background: snow;
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
