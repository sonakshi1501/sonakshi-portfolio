<template>
  <div class="container my-3">
    <heroApp/>
    <aboutSonakshi/>
    <experienceSonakshi/>
    <projectHome/>
    
  </div>
</template>

<script>

import heroApp from "../components/home/Hero.vue";
import aboutSonakshi from "../components/home/AboutSonakshi.vue"
import experienceSonakshi from "../components/home/Experience.vue"
import projectHome from "../components/home/ProjectsHome.vue"
export default {
  name: "AppSonakshiComponent",
  components: {heroApp, aboutSonakshi,experienceSonakshi,projectHome},
  created() {
    document.title="Sonakshi Portfolio"
  }
  
};
</script>

<style>

</style>