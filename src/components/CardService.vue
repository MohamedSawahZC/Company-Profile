<template>
  <div class="main-conatiner">
    <div class="card">
      <img src="../assets/Web.png" alt="" />
      <h4>Mobile Development</h4>
      <h5>
        Perfect design <br />
        with perfect performace
      </h5>
    </div>
  </div>
</template>

<script>
export default {
  name: "Card",
  props: {
    title: String,
  },
};
</script>

<style scoped lang="scss">
.card {
  margin: 0 3rem;
  background-color: white;
  color: #303669;
  height: 25rem;
  width: 20rem;
  border-radius: 20px;
  border: 0;
  transition: all 0.2s;
  &:hover {
    background-color: #1de2cf;
    color: white;
  }
  img {
    margin-top: 1.5rem;
    width: 9rem;
    align-self: center;
    align-content: center;
  }
  h4 {
    font-weight: bold;
    font-size: 1.6rem;
    margin-top: 1.2rem;
    text-align: center;
  }
  h5 {
    margin-top: 2rem;
    text-align: center;
  }
}
</style>