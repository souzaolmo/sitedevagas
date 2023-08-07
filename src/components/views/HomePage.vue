<template>
    <div class="container py-4">
        <div class="row">
          <div class="col">
            <pesquisar-vaga>s</pesquisar-vaga>
          </div>  
        </div>

          <div class="row mt-5">
            <div class="col-4">
              <IndicadorVaga titulo="Vagas abertas" indicador="100" bg="bg-dark" color="text-white"></IndicadorVaga>
            </div>
            <div class="col-4">
              <IndicadorVaga titulo="Profissionais Cadastrados" indicador="225" bg="bg-dark" color="text-white"></IndicadorVaga>
            </div>
            <div class="col-4">
              <IndicadorVaga titulo="Visitantes online" :indicador="usuariosOnline" bg="bg-ligth" color="text-dark"></IndicadorVaga>
              
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
    data: () => ({
      usuariosOnline: 0
    }),
    methods: {
      getUsuariosOnline() {
        this.usuariosOnline = Math.floor(Math.random() *101) // entre 0 e 100
      }
    },
    created() {
      setInterval(this.getUsuariosOnline, 1000) // 1 segundo
    }
  }
  </script>
  
<style >

</style>