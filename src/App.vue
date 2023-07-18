<template>
  <div>
    <h1>Componente App</h1>
    <Topo></Topo>
    <Conteudo></Conteudo>
  </div>
</template>

<script>
import Conteudo_components from './components/layouts/Conteudo_components.vue'
import Topo_components from './components/layouts/Topo_components.vue'

export default {
  name: 'App',
  components: {
    Conteudo: Conteudo_components,
    Topo: Topo_components,
  }
}
</script>

<style>
h1{
  color: red
}
</style>
