<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">{{ nombreEmpresa }}</a>
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarText"
      aria-controls="navbarText"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarText">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="#">Ensaladas</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Arroces</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Pescados</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Carne</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Postres</a>
        </li>
        <li class="nav-item active">
          <a
            class="nav-link"
            href="https://github.com/jcarlosMariscal/Vue-comida-rapida-Examen"
            target="_blank"
            >Código GitHub</a
          >
        </li>
      </ul>
      <span class="navbar-text"> {{ nombreAlumno }} - {{ grupo }} </span>
    </div>
  </nav>
</template>
<script>
// import Grid from "./Grid.vue";
export default {
  props: {
    nombreEmpresa: {
      String,
    },
    nombreAlumno: {
      String,
    },
    grupo: {
      String,
    },
  },
};
</script>
<style scoped>
.navbar-text {
  background-color: rgb(62, 68, 68);
  padding: 5px;
  color: aliceblue;
  font-size: 18px;
}
.navbar-text:hover {
  background-color: transparent;
  padding: 5px;
  color: aliceblue;
  font-size: 18px;
  transition: 0.5s ease-in-out;
  cursor: pointer;
}
</style>
