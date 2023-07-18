<template>
    <div class="container py-4">
        <div class="row">
          <div class="col">
            <div class="h-100 p-5 bg-ligth border rounded-3">
              <h2>Pesquisar Vagas</h2>
              <div class="row">
                <div class="col">
                  <div class="form-group">
                    <label>Título da vaga</label>
                    <input type="tex" class="form-control" placeholder="pesquise por palavras chaves, por exemplo 'PHP', 'Pelno', 'Analista'">
                    <small class="form-text text-muted"> Informe palavras que estejam relacionadas com o titulo da vaga que você proucura</small>
                  </div>
                </div>
              </div>
              <div class="row">
                <div class="col">
                  <button class="btn btn-outline-dark mt2" type="button">Buscar</button>
                </div>
              </div>
            </div>
          </div>
          <div class="row mt-5">
            <div class="col-4">
              <div class="h-100 p-5 rounded-3 border bg-dark text-white">
                <p>Vagas abertas</p>
                <h2>25</h2>
              </div>
            </div>
            <div class="col-4">
              <div class="h-100 p-5 rounded-3 border bg-dark text-white">
                <p>Profissionais cadastrados</p>
                <h2>125</h2>
              </div>
            </div>
            <div class="col-4">
              <div class="h-100 p-5 rounded-3 border bg-ligth text-dark">
                <p>Visitantes online</p>
                <h2>15</h2>
              </div>
            </div>
          </div>
        </div>
    </div>
  
</template>
  
  <script>
  export default {
    name: 'HomePage'
  }
  </script>
  
<style >

</style>