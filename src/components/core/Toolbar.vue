<template>
  
  <nav class="navbar navbar-expand-lg navbar-light " style="border-bottom:1px solid #e0e0e0">
  <div class="container-fluid mx-0">
    <router-link class="navbar-brand" to="/">Sonakshi Shukla</router-link>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <router-link class="nav-link " aria-current="page" to="/">Home</router-link>
        </li>
        
        <li class="nav-item">
          <router-link class="nav-link " aria-current="page" to="/projects">Projects</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link " aria-current="page" to="/talks">Talks</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link " aria-current="page" to="/about">About</router-link>
        </li>
        
        
        
      </ul>
      
    </div>
  </div>
</nav>
</template>

<script>
export default{
    name : "AppFooterComponent",
    data :()=>({

    })
}
</script>

<style>

</style>