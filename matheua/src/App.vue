<script>
import MenuLateral from "@/components/MenuLateral.vue";
import BlocoCabecalho from "./components/BlocoCabecalho.vue";
import BlocoPrincipal from "./components/BlocoPrincipal.vue";
import BlocoFooter from "./components/BlocoFooter.vue";
export default {
  components: { MenuLateral, BlocoCabecalho, BlocoPrincipal, BlocoFooter },
};
</script>

<template>
  <MenuLateral />
  <BlocoCabecalho />
  <BlocoPrincipal />
  <BlocoFooter />
</template>

<style></style>
