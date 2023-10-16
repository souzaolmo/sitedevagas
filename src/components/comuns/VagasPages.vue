<template>
         <div class="card">
          <div class="card-header bg-dark text-white">{{  TituloVagateste }}</div>
          <div class="card-body">
            <p>{{ descricao }}</p>
          </div>
          <div class="card-footer">
            <small class="text-muted"> Salário: R$ {{ salario }}| Modalidade: {{ modalidade }}| Tipo: {{ tipo }} | Publicação: {{ publicacao }}</small>
          </div>
        </div>
</template>

<script> 
export default {
    name: 'VagasPages',
    //props: ['titulo','descricao','salario','modalidade','tipo','publicacao'],
    props: {
      tituloVagateste: String,
      descricaoVaga: String,
      salario: [Number,string],
      modalidade: String,
      tipo: String,
      publicacao: String

    }
}
</script>
