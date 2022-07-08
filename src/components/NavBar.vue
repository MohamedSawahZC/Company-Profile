<template>
  <div class="main-section">
    <!-- ================ Navbar Start ==================================  -->
    <div class="nav-bar">
      <a href="#" class="logo">
        <img src="../assets/logo.png" alt="" />
      </a>
      <ul class="tags">
        <li>
          <a href="#">Home</a>
        </li>
        <li>
          <a href="#">About</a>
        </li>
        <li>
          <a href="#">Projects</a>
        </li>
      </ul>
    </div>
    <!-- ================ Navbar End ==================================  -->

    <!-- ======== Section  ===================== -->
    <div class="row">
      <div class="column">
        <h1 class="header-title">
          Do you search about <br />
          Software Solution?
        </h1>
        <div class="neon-container yellow-neon"></div>
        <p class="header-title2">
          If you are looking for a company that provides you with solutions and
          ideas for programming an application or website, Arab Apps is your
          first choice .. We help you to get everything you need in design,
          programming, technology and business
        </p>
      </div>
      <div class="column">
        <img class="gif" src="../assets/developer.gif" alt="" />
      </div>
    </div>
    <!-- ======== Section  ===================== -->
  </div>
</template>

<script>
export default {
  name: "NavBar",
};
</script>

<style scoped lang="scss">
.main-section {
  padding: 2rem;
  height: calc(100vh - 38vh);
  background: rgb(34, 38, 78);
  background: linear-gradient(
    90deg,
    rgba(34, 38, 78, 1) 0%,
    rgba(39, 43, 83, 1) 41%,
    rgba(60, 65, 107, 1) 100%
  );
  .nav-bar {
    display: flex;
    flex-direction: row;
  }
}
img {
  width: 15rem;
}

.tags {
  display: flex;
  position: absolute;
  right: 1rem;
  flex-direction: row;
  justify-content: flex-end;
  a {
    margin: 0 2rem;
    color: white;
    font-size: 1.5rem;
    font-weight: bold;
    font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    &:hover {
      color: gray;
      text-decoration: none;
    }
  }
}
.header-title {
  color: white;
  font-weight: bold;
  font-size: 3rem;
}
.header-title2 {
  color: white;
  font-size: 1.2rem;
  margin-top: 2rem;
  word-break: break-all;
  max-width: 50%;
}
.neon-container {
  background-color: yellow;
  width: 10rem;
  margin-top: 1.5rem;
  height: 0.8vh;
}
.yellow-neon {
  text-align: center;
  color: rgba(255, 232, 50, 0.9);
  box-shadow: 0 0 10px 1px #cbe731;
  border-radius: 20px;
}
.row {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}
.column {
  margin: 8rem 0rem 4rem 1rem;
}
.gif {
  position: absolute;
  top: 10rem;
  right: 8rem;
  width: 26rem;
}
</style>