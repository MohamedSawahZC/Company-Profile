<template>
  <div id="app">
    <NavBar />
    <VectorShape />
    <SectionForServicesVue />
    <ProjectsSection />
    <FooterSectionVue />
  </div>
</template>

<script>
import NavBar from "./components/NavBar.vue";
import VectorShape from "./components/VectorShape.vue";
import SectionForServicesVue from "./components/SectionForServices.vue";
import FooterSectionVue from "./components/FooterSection.vue";
import ProjectsSection from "@/components/ProjectsSection";
export default {
  name: "App",
  components: {
    NavBar,
    VectorShape,
    SectionForServicesVue,
    FooterSectionVue,
    ProjectsSection,
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  list-style: none;
  text-decoration: none;
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
}
</style>
