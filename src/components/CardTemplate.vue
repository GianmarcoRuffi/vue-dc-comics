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
  padding-bottom: 5px;
}
.card {
  max-width: 200px;
  height: calc(200px + 36px);
  padding: 5px;
  margin-top: 10px;
  margin-bottom: 10px;
  margin-right: 30px;
  text-transform: uppercase;

  &:hover {
    cursor: pointer;
    opacity: 0.8;
  }
}
</style>
