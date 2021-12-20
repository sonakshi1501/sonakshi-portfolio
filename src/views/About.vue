<template>
  <div class="container">
    <div class="row align-items-center my-5">
      <div class="col-md-8">
        <h3>About Sonakshi</h3>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quidem, culpa? Quia aliquid atque animi dolor perferendis at nisi pariatur eos id aspernatur voluptatibus laudantium beatae, magnam vitae optio provident tempora?</p>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Consequatur tempora earum ipsam soluta eos doloribus natus ipsa enim delectus magnam veritatis eligendi autem iusto corrupti tempore, incidunt nobis voluptatum nulla.</p>
        <SocialMedia/>
      </div>
      <div class="col-md-4">
        <img :src="require('@/assets/image/About-removebg-preview.png')" style="width:100%" alt="">
      </div>
    </div>
  </div>
</template>

<script>
import SocialMedia from "../components/common/SocialMedia.vue"
export default {

  name:"AppAbout",
  components:{SocialMedia},
   created() {
    document.title="About | Sonakshi Portfolio"
  }
}
</script>

<style>

</style>
