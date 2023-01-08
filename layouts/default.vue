<template>
  <div>
    <Header></Header>
    <Nuxt />
  </div>
</template>

<script>
import Header from "../components/header.vue";

export default {
  name: "IndexPage",
  components: { Header },
};
</script>

<style></style>
