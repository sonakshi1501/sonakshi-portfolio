<template>
  <div class="card my-2">
          <div class="card-body">
            <h5 class="card-title">{{ pname}}</h5>
            <p class="card-text">{{ pdesc }}</p>
            <a :href="plink" class="card-link">See More</a>
          </div>
        </div>
</template>

<script>
export default {
 name:"AppCardProjects",
 props:["pname","pdesc","plink"]
}
</script>

<style>

</style>