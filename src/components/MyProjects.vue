<template>
    <div class="project">
<nav class="navbar navbar-expand-lg navbar-dark ">
  <router-link to="/HomePage"><li class="navbar-brand text-white" >MFONIDO-MARK</li></router-link>
  <button class="navbar-toggler " type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon "></span>
  </button>
  <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
    <ul class="navbar-nav">
      <li class="nav-item ">
       <router-link to="/About"><a class="nav-link">About <span class="sr-only">(current)</span></a></router-link>
      </li>
      <li class="nav-item active">
        <!-- <a class="nav-link" href="#">Projects</a> -->
      </li>
      <li class="nav-item">
        <a class="nav-link resume" href="assets/Resume.pdf">Resume</a>
      </li>
    </ul>
  </div>
</nav>
<h1 class="text-center text-white pt-5">Project Done</h1>

    </div>
</template>

<style scoped>
.project{
    background-color: black !important;
    height: 100vh;
}
.resume{
    color: red !important;
}
</style>
