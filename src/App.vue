<script>
import MenuLateral from "./components/MenuLateral.vue";
import FootTwister from "@/components/FootTwister.vue";
import CaBeca from "@/components/CaBeca.vue";
import PRincipal from "@/components/PRincipal.vue";
export default {
  components: { MenuLateral, FootTwister, CaBeca, PRincipal },
};
</script>

<template>
  <PRincipal></PRincipal>
  <MenuLateral></MenuLateral>
  <FootTwister />
  <CaBeca />
</template>
