<template>
  <div class="container-fluid">
      <div class="row">
          <div class="col-md-6">
              <h3 class="mb-3">Professional Experiences</h3>
              
              <div v-for="(element,index) in ProfessionalExp" :key= "index">
                  <experienceCard :pname="element.name" :pdegination="element.desigination" :ptimeduration="element.timeduration" :pdescription="element.description"/>
              </div>
          </div>
          <div class="col-md-6">
              <h3 class="mb-3">Community Experiences</h3>
            <div v-for="(element,index) in CommunityExp" :key= "index">
                <experienceCard :pname="element.name" :pdegination="element.desigination" :ptimeduration="element.timeduration" :pdescription="element.description"/>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
import experienceData from "../../assets/data/experience.json" 
import experienceCard from "../common/ExperienceCard.vue"
export default {
    
 name : "AppExperience",
 components :{experienceCard},
 data :()=>({
     ProfessionalExp : experienceData.ProfessionalExperience,
     CommunityExp: experienceData.CommunityExperience
 })
}
</script>

<style>

</style>