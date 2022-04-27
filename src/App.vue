<script>
import MenuLateral from "@/components/MenuLateral.vue";
import MenuCabecalho from "@/components/MenuCabecalho.vue";
import MenuPrincipal from "@/components/MenuPrincipal.vue";
import MenuRodape from "@/components/MenuRodape.vue";

export default {
  components: { MenuLateral, MenuCabecalho, MenuPrincipal, MenuRodape },
};
</script>

<template>
  <MenuLateral />
  <MenuCabecalho />
  <MenuPrincipal />
  <MenuRodape />
</template>
<style></style>
