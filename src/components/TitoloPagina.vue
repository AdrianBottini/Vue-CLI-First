<template>
  <div>
    <h1 class="titolo">
      Ciao a tutti dal componente
    </h1>
  </div>
</template>

<script>
export default {
  name: 'TitoloPagina',
};
</script>

<style lang="scss" scoped>
$title_color: red;

div {
 background-color: blue;
  .titolo {
    color: $title_color;
  }
}
</style>
