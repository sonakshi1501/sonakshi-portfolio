<template>
  <div class="container">
    <div class="row my-5">
      <div class="col-md-12">
        <h3>My Talks</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia placeat eaque voluptates quos, dolorum temporibus consequuntur aliquam suscipit vero impedit culpa, quae ratione architecto blanditiis id eius quo? Itaque, quasi?</p>
      </div>
    </div>
    <div class="row my-5">
      <div class="col-md-12">
          <talkstable/>
      </div>
    </div>
  </div>
</template>

<script>
import talkstable from "../components/common/TalksTable.vue"

export default {

  name: "AppTalks",

  components: {talkstable},
  data: () => ({
  }),
   created() {
    document.title="Talks | Sonakshi Portfolio"
  }
};
</script>

<style>
</style>