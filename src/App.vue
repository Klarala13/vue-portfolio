<template>
  <div>
    <div>
      <app-header></app-header>
    </div>
    <div>
      <app-jumbotron></app-jumbotron>
      <projects></projects>
      <skills></skills>
      <contact></contact>
      <appFooter></appFooter>
    </div>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Jumbotron from "./components/Jumbotron.vue";
import Projects from "./components/projects/Projects.vue";
import Skills from "./components/Skills/Skills.vue";
import Contact from "./components/Contact.vue";
import Footer from "./components/Footer.vue";

export default {
  components: {
    appHeader: Header,
    appJumbotron: Jumbotron,
    projects: Projects,
    skills: Skills,
    contact: Contact,
    appFooter: Footer,
  },
};
</script>

<
