<script setup>
import ListagemLivros from '@/components/ListagemLivros.vue'
import MeuCarrinho from '@/components/MeuCarrinho.vue'
</script>

<template>
  <h1>Bolas.com II</h1>
  <div class="container-geral">
    <listagem-livros />
      

  </div>
  <hr>
  <meu-carrinho />


</template>

<style scoped>
.container-geral {
  display: grid;
  grid-template-columns: 3fr 1fr;
}
h1{
  text-align: center;
}
</style>
