<template>
    <div>
      <h1>Componente Conteudo</h1>
      <home-page></home-page>
      <publicar-vaga></publicar-vaga>
     
    </div>
  
  </template>
  
  <script>
  import HomePage from '../views/HomePage.vue'
  import PublicarVaga from '../views/PublicarVaga.vue'
  export default { 
    name: 'Conteudo_components',
    components: {
      HomePage,
      PublicarVaga
    }
  }
  </script>
  
  <style ></style>