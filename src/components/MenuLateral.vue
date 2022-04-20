<script>
export default {
  data() {
    return {
      items: ["Brinquedos", "Louças", "Perfumaria"],
    };
  },
};
</script>
<template>
  <aside id="sidenav">
    <ul>
      <li v-for="(item, i) of items" :key="i">{{ item }}</li>
    </ul>
  </aside>
</template>
