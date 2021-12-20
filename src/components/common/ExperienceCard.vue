<template>
  <div
    class="pb-3 mb-3"
    style="border-bottom: 1px solid #e0e0e0"
  >
    <p class="mb-0" style="font-size: 110%">{{ pname }}</p>
    <p class="my-0" style="font-size: 105%">{{ pdesigination }}</p>
    <p class="my-0" style="font-size: 80%">{{ ptimeduration }}</p>
    <p class="my-0" style="font-size: 90%">{{ pdescription }}</p>
  </div>
</template>

<script>
export default {
    name : "AppExperienceCard",
    props : ["pname","pdegination","ptimeduration","pdescription"]

};
</script>

<style>
</style>