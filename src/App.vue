<template>
  <main class="columns is-gapless is-multiline">
    <div class="colimn is-one-quarter">
      <barra-lateral />
    </div>
    <div class="column is-three-quarter">
      <Formulario />
    </div>
  </main>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import BarraLateral from './components/BarraLateral.vue';
import Formulario from './components/Formulario.vue';


export default defineComponent({
  components: { BarraLateral, Formulario },
  name: 'App'
});
</script>

<style>

</style> 
