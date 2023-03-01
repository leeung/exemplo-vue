<script lang="ts">
//import HelloWorld from './components/HelloWorld.vue'
//import TheWelcome from './components/TheWelcome.vue'

import { defineComponent } from 'vue';
import HelloWorld from './components/HelloWorld.vue'
import Produtos from './components/Produtos.vue'

import BarraLateral from './components/BarraLateral.vue';

export default defineComponent({
    name: "App",
    components:{
      HelloWorld,
      BarraLateral
    }
});

</script>

<template>
  <main class="columns is-gapless is-multiline">
    <div class="column is-one-quarter">
      <BarraLateral/>
    </div>
  </main>
</template>

<style scoped>

</style>
