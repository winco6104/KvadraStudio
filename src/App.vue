<template>
  <div class="app">
    <header-component></header-component>
    <section-create></section-create>
    <section-comfort></section-comfort>
    <section-portfolio></section-portfolio>
    <section-about></section-about>
    <section-works></section-works>
    <view-projects></view-projects>
    <section-tech-research></section-tech-research>
    <section-interior></section-interior>
    <section-cards></section-cards>
    <section-definition></section-definition>
    <section-about-us></section-about-us>
    <section-interer></section-interer>
    <section-design></section-design>
    <section-form></section-form>
    <section-footer></section-footer>
  </div>
</template>
<script>
import HeaderComponent from "@/components/Header.vue";
import sectionPortfolio from "@/components/sectionPortfolio.vue";
import sectionAbout from "@/components/sectionAbout.vue";
import sectionCreate from "@/components/sectionCreate.vue";
import sectionComfort from "@/components/sectionComfort.vue";
import sectionWorks from "@/components/sectionWorks.vue";
import ViewProjects from "./components/UI/viewProjects.vue";
import SectionTechResearch from './components/sectionTechResearch.vue';
import sectionDefinition from './components/sectionDefinition.vue';
import sectionCards from "./components/sectionCards.vue";
import SectionInterior from "@/components/sectionInterior";
import sectionAboutUs from "@/components/sectionAboutUs.vue";
import SectionInterer from "@/components/sectionInterer.vue";
import SectionDesign from './components/section_Design.vue';
import SectionForm from './components/sectionForm.vue';
import SectionFooter from './components/sectionFooter.vue';


export default {
  components: {
    HeaderComponent,
    sectionPortfolio,
    sectionAbout,
    sectionWorks,
    ViewProjects,
    sectionCreate,
    sectionComfort,
    SectionTechResearch,
    sectionCards,
    SectionInterior,
    sectionAboutUs,
    SectionInterer,
    SectionDesign,
    // SectionDesign,
    sectionDefinition,
    SectionForm,
    SectionFooter,
  },
};
</script>
<style src="@/styles/main.css"></style>
