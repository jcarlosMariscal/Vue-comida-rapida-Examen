<template>
  <headerNav
    nombreEmpresa="La Cocina de Elisa"
    nombreAlumno="Juan Carlos Ramírez Mariscal"
    grupo="10A"
  />
  <div class="container">
    <card
      url="https://www.clara.es/medio/2021/12/16/que-comer-hoy-ideas_21beeb02_1200x630.jpg"
      nombre="Espirales con verduras"
      descripcion="Puedes espiralizar verduras como calabacines, calabazas, zanahorias, pepinos, patatas, remolachas, pimientos o cebollas, y frutas de consistencia fuerte, como la manzana, el melón o la pera."
      costo="$50.00"
    />
    <card
      url="https://i.blogs.es/c6b6ab/marineras2/1366_2000.jpg"
      nombre="Marinera murciana"
      descripcion="La marinera es la tapa murciana por antonomasia, imprescindible en la carta de cualquier bar o cafetería. Es un básico del aperitivo, del tapeo o del tardeo, que realmente apetece a casi cualquier hora."
      costo="$100.00"
    />
    <card
      url="https://www.cardamomo.news/__export/1617049023979/sites/debate/img/2021/03/29/receta_de_alambre_de_res_con_queso_y_pimientosx_comida_mexicana.jpeg_430732068.jpeg"
      nombre="Alambre de res con queso"
      descripcion="Los alambres son carne cortada en tacos, un equivalente a las brochetas que se pueden cocinar o una especie de estofado. Con un ingrediente como la carne de res podemos preparar una comida."
      costo="$100.00"
    />
    <card
      url="https://www.cardamomo.news/__export/1617049210780/sites/debate/img/2021/03/29/ceviche_de_soya_con_catsupx_receta_econxmica_lista_en_15_minutos.jpeg_430732068.jpeg"
      nombre="Ceviche de soya con catsup"
      descripcion="Plato de pescado o marisco crudo cortado en trozos pequeños y puestos a marinar en un preparado de adobo de jugo de limón o naranja agria, cebolla picada, sal, pimienta y cilantro."
      costo="$100.00"
    />
    <card
      url="https://www.cardamomo.news/__export/1617050565228/sites/debate/img/2021/03/29/receta_de_sopa_de_lentejas_con_salchichax_fxcil_en_15_minutos.jpeg_430732068.jpeg"
      nombre="Sopa de lentejas con salchicha"
      descripcion="Es rica en hierro, manganeso, potasio, zinc, cobre, fósforo, selenio y calcio. También aportan la mayor parte de nuestro requerimiento de ácido fólico y contribuyen con una buena cantidad de las recomendaciones de ingesta de vitaminas A."
      costo="$100.00"
    />
    <card
      url="https://www.cardamomo.news/__export/1617051023090/sites/debate/img/2021/03/29/receta_de_pollo_empanizado_crujiente_sin_harinax_paso_a_paso.jpeg_430732068.jpeg"
      nombre="Pollo empanizado"
      descripcion="Cubrir con pan molido un alimento para freírlo. Esta técnica se utiliza mucho en la cocina mexicana: se empanizan bisteces, pechugas de pollo, filetes de pescado, camarones y algunas verduras."
      costo="$100.00"
    />
  </div>
  <myFooter fecha="Clase 22-09-2022 | Exámen" />
</template>
<script>
import HeaderNav from "./components/HeaderNav.vue";
import Card from "./components/Card.vue";
import MyFooter from "./components/MyFooter.vue";
export default {
  components: { Card, HeaderNav, MyFooter },
};
</script>
