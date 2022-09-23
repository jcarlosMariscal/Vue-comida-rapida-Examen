<template>
  <footer class="bg-primary text-center text-lg-start sectionFooter">
    <div>
      <p>DONDE ESTAMOS</p>
      <p>C/Pedro Damian</p>
      <p>23258 Madrid</p>
      <p>T.447447</p>
      <p>Enlace a Google maps</p>
    </div>
    <div>
      <p>HOME</p>
      <p>OBRA DIVIERNO</p>
      <p>MENU</p>
      <p>RESERVAS</p>
    </div>
    <div>
      <P>CONTACTO</P>
      <P>info@diverso.com</P>
      <P>info@diverso.com</P>
      <P>info@diverso.com</P>
    </div>
    <div>
      <p>AVISO LEGAL</p>
      <p>PRIVACIDAD</p>
      <P>© 2020 Copyright: MDBootstrap.com</P>
    </div>
    <div>
      <P>TIH COLLECTION</P>
    </div>
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
<style scoped>
.sectionFooter {
  display: flex;
  flex-direction: row;
  height: 200px;
}
.sectionFooter div {
  width: 20%;
  display: flex;
  flex-direction: column;
  align-items: center;
  align-content: center;
  justify-content: center;
  justify-items: center;
}
.sectionFooter div p {
  margin: 0;
  color: aliceblue;
}
</style>
