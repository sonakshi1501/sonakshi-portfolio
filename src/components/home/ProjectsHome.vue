<template>
  <div class="container-fluid">
      <div class="row my-5">
      <div class="container-fluid">
        <div class="row">
          <div class="col-md-12">
            <h3>Projects</h3>
            <p>I have created various projects and below is some of my project</p>
          </div>
        </div>
        <div class="row">
          <div
            class="col-md-4"
            v-for="(element, index) in projects.slice(0, 3)"
            :key="index"
          >
            <projectCard
              :pname="element.name"
              :pdesc="element.desc"
              :plink="element.link"
            />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import projectsData from "../../assets/data/projects.json" ;
import projectCard from "../common/ProjectCard.vue";
export default {
    name:"AppPrpojectHome",
    components :{projectCard},
    data: () => ({
    projects: projectsData,
   
  }),
}
</script>

<style>

</style>