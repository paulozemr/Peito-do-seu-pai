<script>
export default {
  data() {
    return {
      items: [
        "Hora de Aventura",
        "Apenas um Show",
        "Incrivel Mundo de Gumball",
        "Steven Universo",
        "Gravity Falls",
        "Rick and Morty",
      ],
    };
  },
};
</script>
<template>
  <aside id="sidenav">
    <h3>Lista de desenhos</h3>
    <ul>
      <li v-for="(item, i) of items" :key="i">{{ item }}</li>
    </ul>
  </aside>
</template>
<style>
li {
  color: rgb(106, 106, 243);
}
h3 {
  padding-left: 45px;
  color: blue;
}
</style>
