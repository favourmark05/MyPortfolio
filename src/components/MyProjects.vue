<template>
    <div class="bg-dark">

         <section class="nav-section">

        <nav class="navbar navbar-expand-lg navbar-light ">
            <div class="container">
                <a class="navbar-brand text-white" href="index.html">MFONIDO MARK</a>
                <button class="navbar-toggler icon" type="button" data-toggle="collapse"
                    data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false"
                    aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon icon"></span>
                </button>
                <div class="collapse navbar-collapse justify-content-end" id="navbarNavDropdown">
                    <ul class="navbar-nav">
                        <li class="nav-item active">
                            <router-link to="/MyProjects" class="nav-link active-now">Projects<span class="sr-only">(current)</span></router-link>
                        </li>
                        <li class="nav-item">
                            <router-link to="/ContactMe" class="nav-link">Contact</router-link>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link active-now resume" href="/assets/Resume.pdf">Resume</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </section>
<!-- the end of the nav-bar section -->

<h1 class="text-center text-white text-bolder  py-5 " style="text-decoration: underlin; font-weight: bolder; font-size: 50px;">LIST OF PROJECT DONE</h1>
<!-- this is the start of the card section -->
    <!-- <section class="card-sect py-5"> -->
            <div class="container mt-4 mb-4">
                    <div class="row mx-auto">
                        <div class="col-md-4 py-3 px-3">
                        <div class="card card-project " style="width: 30rem; height: 43rem;">
                                <img src="/assets/ghostApp.png" class="card-img-top" alt="...">
                                <div class="card-body">
                                  <h5 class="card-title">Word Encrypting Application</h5>
                                  <p class="card-text">A simple Appliication that lets you send encrypted messages to friends. You can also decrypt encrypted messages generated from this tool, built with JS.</p>
                                  <small>JavaScript</small> <br>
                                  <a href="https://github.com/favourmark05/ghost" target="_blank" class="btn btn-primary">CODE BASE</a>&nbsp;&nbsp;
                                  <a href="https://ghostmood.netlify.app/" target="_blank"  class="btn btn-primary">APPLICATION</a>
                                </div>
                              </div>
                              </div>

                        <div class="col-md-4 py-3 px-3">
                        <div class="card card-project " style="width: 30rem; height: 43rem;">
                                <img src="/assets/calculator.png" class="card-img-top" alt="...">
                                <div class="card-body">
                                  <h5 class="card-title">Calculator</h5>
                                  <p class="card-text">A simple calculator with basic math operations built with javascript and responsive for all screen sizes.</p>
                                  <small>JavaScript</small> <br>
                                  <a href="https://github.com/favourmark05/MyResponsiveCalculator" target="_blank"  class="btn btn-primary">CODE BASE</a> &nbsp;&nbsp;
                                  <a href="https://markcalculator.netlify.app/" target="_blank"  class="btn btn-primary">APPLICATION</a>
                                </div>
                              </div>
                              </div>

                       <div class="col-md-4 py-3 px-3">
                        <div class="card card-project " style="width: 30rem;height: 43rem;">
                                <img src="/assets/src.png" class="card-img-top" alt="..." >
                                <div class="card-body">
                                  <h5 class="card-title">Student Union</h5>
                                  <p class="card-text">The official webpage of the student union goverment of Obong University, for information dissemination of the activities of the union.</p>
                                  <small>Html5,Css3,JavaScript</small> <br>
                                  <a href="https://github.com/favourmark05/src" target="_blank"  class="btn btn-primary">CODE BASE</a>&nbsp;&nbsp;
                                  <a href="https://srcobonguniversity.netlify.app/" target="_blank"  class="btn btn-primary">APPLICATION</a>
                                </div>
                              </div>
                             </div>
                    </div>
                </div>

    </div>
</template>

<style scoped>
.bg-dark{
    background-color: black !important;
    height: 110vh !important;
}
</style>
