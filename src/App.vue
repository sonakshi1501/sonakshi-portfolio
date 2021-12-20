<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-md-12">
        <AppToolbar/>
        
    <router-view> </router-view>
      <AppFooter/>
      </div>
    </div>
  </div>
</template>

<script>
import AppToolbar from "./components/core/Toolbar.vue"
import AppFooter from "./components/core/Footer.vue"
export default {
  name: "AppComponent",
  components:{
    AppToolbar,
    AppFooter,
  },
  data: ()=>({

  })
}
</script>

<style>

</style>