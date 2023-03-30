<template>
  <section>
    <h1>🚀 Compre ou Venda 💸</h1>
    <produtos-buscar-vue />
    <produtos-lista-vue />
  </section>
</template>

<script>
import ProdutosBuscarVue from "@/components/ProdutosBuscar.vue";
import ProdutosListaVue from "@/components/ProdutosLista.vue";

export default {
  name: "HomeView",
  components: {
    ProdutosBuscarVue,
    ProdutosListaVue,
  },
};
</script>

<style scoped>
h1 {
  font-size: 2rem;
  color: #87f;
  margin-top: 40px;
  text-align: center;
}
</style>
