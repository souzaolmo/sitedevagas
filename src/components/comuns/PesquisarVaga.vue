<template>
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
</template>

<script>
export default {
    name: 'PesquisarVaga'
}
</script>