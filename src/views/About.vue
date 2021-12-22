<template>
  <div class="container">
    <div class="row align-items-center my-5">
      <div class="col-md-8">
        <h3>About Sonakshi</h3>
        <p>
          I am “Sonakshi Shukla,” Inquisitive person. I did my B-tech from
          Lovely Professional University. I started my journey from basics by
          learning C and got to know about multiple languages for building Web
          Application and the roller coaster ride started from HTML to CSS and
          to JS and now I am wondering around frameworks.
        </p>
        <p>
          I am a facile person who is always ready to learn and wants to justify
          the technology on which I am working. With the idea of learning and
          exploring myself, it is helping me to reach my goal.
        </p>
        <SocialMedia />
      </div>
      <div class="col-md-4">
        <img
          :src="require('@/assets/image/About-removebg-preview.png')"
          style="width: 100%"
          alt=""
        />
      </div>
    </div>
  </div>
</template>

<script>
import SocialMedia from "../components/common/SocialMedia.vue";
export default {
  name: "AppAbout",
  components: { SocialMedia },
  created() {
    document.title = "About | Sonakshi Portfolio";
  },
};
</script>

<style>
</style>
