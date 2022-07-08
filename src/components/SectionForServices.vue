<template>
  <div class="section">
    <h1>Service</h1>
    <h4>What we're provide</h4>
    <div class="cards">
      <CardServiceVue v-bind:title="Web" />
      <CardServiceVue />
      <CardServiceVue />
    </div>
  </div>
</template>

<script>
import CardServiceVue from "./CardService.vue";
export default {
  name: "section",
  components: {
    CardServiceVue,
  },
};
</script>
<style lang="scss" scoped>
.section {
  height: 80vh;
  margin-top: 10rem;
  h1,
  h4 {
    text-align: center;
    font-weight: bold;
    font-size: 4rem;
    color: #22264e;
  }
  h4 {
    font-size: 2rem;
    margin: 1rem 0 4rem 0;
  }
  .cards {
    display: flex;
    flex-direction: row;
    justify-content: center;
  }
}
</style>