<template>
  <div class="container">
    <div class="row my-5">
      <div class="col-md-12">
        <h3>My Talks</h3>
        <p>I got opportunity to be part of wounderful events, where i leraned many technology and also made other learn about new technology. This give an take journey was full of joy and experiences. I have mentioned some of my events.</p>
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