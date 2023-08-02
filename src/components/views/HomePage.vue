<template>
    <div class="container py-4">
        <div class="row">
          <div class="col">
            <pesquisar-vaga>s</pesquisar-vaga>
          </div>  
        </div>

          <div class="row mt-5">
            <div class="col-4">
              <IndicadorVaga titulo="Vagas abertas" indicador="100"></IndicadorVaga>
            </div>
            <div class="col-4">
              <IndicadorVaga titulo="Profissionais Cadastrados" indicador="225"></IndicadorVaga>
            </div>
            <div class="col-4">
              <IndicadorVaga titulo="Visitantes online" indicador="25"></IndicadorVaga>
            </div>
          </div>
    </div>
  
</template>
  
  <script>
  import IndicadorVaga from '@/components/comuns/IndicadorVaga.vue'
  import PesquisarVaga from '@/components/comuns/PesquisarVaga.vue'
  
  export default {
    name: 'HomePage',
    components: {
      PesquisarVaga,
      IndicadorVaga
    },
  }
  </script>
  
<style >

</style>