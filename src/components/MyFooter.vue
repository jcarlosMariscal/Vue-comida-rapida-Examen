<template>
  <footer class="bg-primary text-center text-lg-start">
    <!-- Copyright -->
    <div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2)">
      © 2020 Copyright:
      <a class="text-dark" href="https://mdbootstrap.com/">MDBootstrap.com</a>
      <p>-{{ fecha }}</p>
    </div>
    <!-- Copyright -->
  </footer>
</template>
<script>
// import Grid from "./Grid.vue";
export default {
  props: {
    fecha: {
      String,
    },
  },
};
</script>
