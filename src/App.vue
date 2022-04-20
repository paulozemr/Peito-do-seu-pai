<script>
import MenuLateral from "./components/MenuLateral.vue";
import FootTwister from "@/components/FootTwister.vue";
import Cabeca from "@/components/Cabeca.vue";
import principal from "@/components/principal.vue";
export default {
  components: { MenuLateral, FootTwister, Cabeca, principal },
};
</script>

<template>
  <principal></principal>
  <MenuLateral></MenuLateral>
  <FootTwister />
  <Cabeca />
</template>
