<cv-content id="#main-content">
  <router-view />
</cv-content>

<script>
import TutorialHeader from "./components/TutorialHeader";

export default {
  name: "App",
  components: {
    TutorialHeader
  }
};
</script>

<template>
  <div id="app">
    <tutorial-header />
    <cv-content id="#main-content">
      <cv-button>Button</cv-button>
    </cv-content>
  </div>
</template>


<template>
  <div id="app">
    <CvButton>Button</CvButton>
  </div>
</template>

<style lang="scss"></style>

<style lang="scss">
@import "./styles/carbon";
</style>
