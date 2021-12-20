<template>
  <div class="container-fluid">
    <div class="row my-5">
      <div
        class="col-md-12 text-center p-4 pb-5"
        style="background-color: #fafafa; border-redius: 25px"
      >
        <h2>I am working on</h2>
        <p>
          I am an aspiring software engineer who is passionate about coding. My
          inquisitive mind always triggers me to identify the codes of any
          software I come across. I am passionate about Python and C++. Looking
          for a role where I can grow and learn from experienced team members
          while drawing on project experience I have already successfully
          executed.
        </p>
        <span class="mychip" v-for="(element, index) in skills" :key="index">
          {{ element }}
        </span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppAboutSonakshi",
  data: () => ({
    skills: [
      "HTML",
      "CSS",
      "Java Script",
      "Bootstrap",
      "Vue.js",
      "Action On Google",
    ],
  }),
};
</script>

<style>
.mychip {
  border: 1px solid black;
  margin-right: 8px;
  border-radius: 50px;
  padding-left: 12px;
  padding-right: 10px;
  text-align: center;
  padding-bottom: 5px;
  
}
</style>