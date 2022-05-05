<template>
  <div class="card">
    <img :src="src" alt="" />
    <h4>{{ title }}</h4>
  </div>
</template>

<script>
export default {
  name: "CardTemplate",
  props: ["src", "title"],
};
</script>

<style scoped lang="scss">
img {
  height: 200px;
  width: 200px;
  object-fit: cover;
  object-position: top;
}
.card {
  max-width: 200px;
  padding: 5px;
}
</style>
