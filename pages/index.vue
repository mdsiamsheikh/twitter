<template>
  <div class="contaner">
    <middle-sidebar></middle-sidebar>
    <rightSideberVue></rightSideberVue>
  </div>
</template>

<script>
import middleSidebarVue from "../components/middleSidebar.vue";
import rightSideberVue from "../components/rightSideber.vue";
export default {
  name: "IndexPage",
  components: {
    middleSidebarVue,
    rightSideberVue,
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  display: flex;
  height: 100vh;
  max-width: 1300px;
  margin-left: auto;
  margin-right: auto;
  /* padding: 0 10px; */
}
</style>
