<template>
  <div class="container-fluid text-center">
    <div class="row">
      <div class="col-md-4 text-center">
        <img
          src="https://pbs.twimg.com/profile_images/1045289571389399041/J5mGRipa_400x400.jpg"
          style="border-radius: 50%; border: 5px solid #4a4a; width: 70%"
          alt=""
        />
      </div>
      <div class="col-md-8 my-5">
        <h2>Sonakshi Shukla</h2>
        <p>
          I am an aspiring software engineer who is passionate about coding. My
          inquisitive mind always triggers me to identify the codes of any
          software I come across. I am passionate about Python and C++. Looking
          for a role where I can grow and learn from experienced team members
          while drawing on project experience I have already successfully
          executed.
        </p>
      </div>
    </div>
    <div class="row my-5">
      <div class="col-md-12 text-center ">
        <h2>About</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Iste,
          delectus quibusdam harum deserunt sed debitis laboriosam nostrum
          reprehenderit at dolor deleniti neque minima beatae alias rem esse
          veniam nemo minus!
        </p>
      </div>
    </div>
    <div class="row my-5">
      <div class="container-fluid">
        <div class="row">
          <div class="col-md-12">
            <h2>Projects</h2>
          </div>
        </div>
        <div class="row">
          <div
            class="col-md-4"
            v-for="(element, index) in projects.slice(0,3)"
            :key="index">
            <projectCard :pname="element.name" :pdesc="element.desc" :plink="element.link" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

import projectsData from "../assets/data/projects.json"
import projectCard from "../components/common/ProjectCard.vue"
export default {
  name: "AppSonakshiComponent",
  components:{projectCard},
  data: () => ({
    projects: projectsData
  }),
};
</script>

<style>
</style>