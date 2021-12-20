<template>
  <div class="container">
    <div class="row my-5">
      <div
        class="col-md-4"
        v-for="(element, index) in projects"
        :key="index">
        <projectCard :pname="element.name" :pdesc="element.desc" :plink="element.link" />
      </div>
    </div>
  </div>
</template>

<script>
import projectsData from "../assets/data/projects.json";
import projectCard from "../components/common/ProjectCard.vue"

export default {

  name: "AppProjects",
  components: {projectCard},
  data: () => ({
    projects: projectsData,
  }),
};
</script>

<style>
</style>