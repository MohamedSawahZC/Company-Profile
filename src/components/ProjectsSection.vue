<template>
  <!--  ======================= Project Area =============================  -->

  <section class="project-area">
    <div class="container">
      <div class="project-title pb-5">
        <h1 class="text-uppercase title-h1">Recently Done Project</h1>
        <h1 class="text-uppercase title-h1">Quality Work</h1>
      </div>

      <div class="row grid">
        <div class="col-lg-4 col-md-6 col-sm-12 element-item latest">
          <div class="our-project">
            <div class="img">
              <a class="test-popup-link" href="../img/portfolio/p1.jpg">
                <img
                  src="../img/portfolio/p1.jpg"
                  alt="portfolio-1"
                  class="img-fluid"
                />
              </a>
            </div>
            <div class="title py-4">
              <h4 class="text-uppercase">Minimul Desing</h4>
              <span class="text-secondary">Latest, Portfolio</span>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 col-sm-12 element-item latest">
          <div class="our-project">
            <div class="img">
              <a class="test-popup-link" href="../img/portfolio/p1.jpg">
                <img
                  src="../img/portfolio/p1.jpg"
                  alt="portfolio-1"
                  class="img-fluid"
                />
              </a>
            </div>
            <div class="title py-4">
              <h4 class="text-uppercase">Minimul Desing</h4>
              <span class="text-secondary">Latest, Portfolio</span>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-6 col-sm-12 element-item latest">
          <div class="our-project">
            <div class="img">
              <a class="test-popup-link" href="../img/portfolio/p1.jpg">
                <img
                  src="../img/portfolio/p1.jpg"
                  alt="portfolio-1"
                  class="img-fluid"
                />
              </a>
            </div>
            <div class="title py-4">
              <h4 class="text-uppercase">Minimul Desing</h4>
              <span class="text-secondary">Latest, Portfolio</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Projects",
};
</script>

<style lang="scss" scoped>
.site-main .services-area {
  padding: 7rem 2rem;
}

.site-main .services-area .services-title {
  padding: 0 14rem;
}

.site-main .services-area .services-title h1 {
  font-size: 35px;
}

.site-main > .services-area .services {
  background: rgba(248, 252, 253, 0.973);
  padding: 2rem 0;
  width: 16rem;
  margin: 5rem 0.5rem;
  transition: box-shadow 0.7s ease;
}

.site-main > .services-area .services:hover {
  box-shadow: var(--box-shadow);
}
.project-title {
  text-align: center;
}
</style>