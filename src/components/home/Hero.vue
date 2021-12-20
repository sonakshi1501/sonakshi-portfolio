<template>
  <div class="container-fluid">
      <div class="row align-items-center my-5">
      <div class="col-md-4 text-center">
        <img
          src="https://pbs.twimg.com/profile_images/1045289571389399041/J5mGRipa_400x400.jpg"
          style="border-radius: 50%; border: 3px solid #4285f4 ; width: 70%"
          alt=""
        />
      </div>
      <div class="col-md-8">
        <h2>Hello!</h2>
        <h3>I'm Sonakshi</h3>
        <h3>Front End Developer</h3>
        <h4>UX/UI Designer</h4>

        <p>
          Always eager to learn new technologies and develop new things based on it.
        </p>
        <SocialMedia/>
      </div>
    </div>
  </div>
</template>

<script>
import SocialMedia from "../common/SocialMedia.vue";
export default {
    components : {SocialMedia},
 name : "AppHero"
}
</script>

<style>

</style>