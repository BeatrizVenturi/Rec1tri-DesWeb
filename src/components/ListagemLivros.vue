<script setup>
import { livros } from '@/_data/livros.js'
import { adicionarAoCarrinho } from '@/_data/carrinho.js'

import CardLivro from '@/components/CardLivro.vue'
</script>

<template>
  <div class="listagem-livros">
    <card-livro v-for="livro in livros" v-bind:key="livro.id" v-bind:livro="livro"
      @adicionarAoCarrinho="adicionarAoCarrinho" />

    <div class="navBar">
      <ul class="nav flex-column">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Active</a>
        </li>
      </ul>
      adkjaojdvsj
    </div>

  </div>
</template>

<style scoped>
.navBar{
  text-align: right;
}

.listagem-livros {
  display: flex;
  flex-wrap: wrap;
  text-align: center;
}
</style>
