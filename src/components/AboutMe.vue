<template>
    <div>
        <header id="header">
    <div class="about-welcome-sect">
      <section class="nav-section">

        <nav class="navbar navbar-expand-lg navbar-light ">
          <div class="container">
            <a class="navbar-brand text-white" href="index.html">MFONIDO MARK</a>
            <button class="navbar-toggler icon" type="button" data-toggle="collapse" data-target="#navbarNavDropdown"
              aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon icon"></span>
            </button>
            <div class="collapse navbar-collapse justify-content-end" id="navbarNavDropdown">
              <ul class="navbar-nav">
                <li class="nav-item active">
                  <!-- <a class="nav-link" href="project.html">Projects <span class="sr-only">(current)</span></a> -->
                    <router-link to="/MyProjects" class="nav-link">Projects<span class="sr-only">(current)</span></router-link>
                </li>
                <li class="nav-item">
                  <!-- <a class="nav-link" href="contact.html">Contact</a> -->
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
      <h1 class="text-center pro">Profile</h1>
    </div>
  </header>
  <div class="container text-center pt-5">
    <div class="card mb-3 shadow" style="max-width: fit-content; max-height: fit-content;">
      <div class="row no-gutters">
        <div class="col-md-4">
          <img src="/assets/about.jpg" class="card-img" alt="..." style="height: 100%;">
        </div>
        <div class="col-md-8">
          <div class="card-body">
            <h3 class="card-title">About me</h3>
            <p class="card-text " id="card-text">Hello, i'm Mfonido Friday Mark.<br> I design thoughtful digital experiences &
              beautiful brand aesthetics. I provide high quality web design, graphics services, digital marketing and
              online advert for Businesses and Personal Brands. Hire me to build you a website,design your graphic works
              teach you to code or speak at your event. </p>
            <!-- <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p> -->
            <br><br>
            <div class="about-info">
              <p><span class="title-s">Name: </span> <span>Mfonido Mark</span></p>
              <p><span class="title-s">Profile: </span> <span>frontend developer</span></p>
              <p><span class="title-s">Email: </span> <span>favourmark05@gmail.com</span></p>
              <p><span class="title-s">Phone: </span> <span>+2349096906695, +2349034754819</span></p>
              <p><span class="title-s">Leadership Position: </span> <span>Ingressive Campus Ambassador, Obong
                  University</span></p>
              <p><span class="title-s">Leadership Position: </span> <span>Director of Software (nacoss) Obong
                  University</span></p>
              <p><span class="title-s">Leadership Position: </span> <span>Director of information (SUG) Obong
                  University</span></p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="container mx-auto py-5">
    <div class="col-md-10 ">
      <table class="table">
        <thead>
          <tr>
            <th scope="col">Skills</th>
            <th scope="col">Tools</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>HTML5, CSS3</td>
            <td>GIT/GITHUB</td>

          </tr>
          <tr>
            <td>BOOTSTRAP</td>
            <td>NETLIFY</td>
          </tr>
          <tr>
            <td>JAVASCRIPT</td>
            <td>COREL DRAW</td>
          </tr>
          <tr>
            <td>VUEJS/NUXTJS</td>
            <td>FIGMA</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>

<footer>
  <div class="col text-center bg-dark text-white"> © 2020 Copyright: Mfonido Mark</div>
</footer>
    </div>
</template>

<style>
.pro{
    color: white;
    font-size: 15vh;
    padding-top: 20vh;
    padding-bottom: 30vh;
    text-align: center;
    /* font-family: 'Pacifico', cursive !important; */
}
/* Global stylings */
html{
    box-sizing: border-box;
    font-size: 62.5%;
    scroll-behavior: smooth
}
*,
*::after,
*::before{
    margin: 0;
    padding: 0;
    box-sizing: inherit;
}
a,a::after,
a::before, a:link{
    text-decoration: none;
    color: white;
}

a:hover{
    text-decoration: none;
    color: white;
}
.Mark {
    text-decoration: none !important;
    color: white !important;
    font-size: 30px !important;
    font-weight: bolder !important;
}

body{
    font-family: sans-serif;
    font-weight: 400;
    font-size: 18px;
    line-height: 1.7;
    color: #777;
    overflow-x: hidden;
    position: relative;
}
.navbar, .nav-link{
    color: #fff;
    font-weight: 400;
    font-size: 18px;
}
.navbar{
    transition: background-color 1s;
}
.nav-logo{
    float: left;
    padding: 10px 15px;
}
.open-nav{
    float: right !important;
    padding: 10px 15px;;
}

/* Overlay Navigation styling here */
.overlay {
    height: 100%;
    width: 0;
    position: fixed;
    z-index: 1;
    top: 0;
    left: 0;
    background-color: rgb(0,0,0);
    background-color: rgba(0,0,0, 0.9);
    overflow-x: hidden;
    transition: 0.5s;
  }

  .overlay-content {
    position: relative;
    top: 25%;
    width: 100%;
    text-align: center;
    margin-top: 30px;
  }

  .overlay a {
    padding: 8px;
    text-decoration: none;
    font-size: 36px;
    color: #818181;
    display: block;
    transition: 0.3s;
  }

  .overlay a:hover, .overlay a:focus {
    color: #f1f1f1;
  }

  .overlay .closebtn {
    position: absolute;
    top: 20px;
    right: 45px;
    font-size: 60px;
  }

  @media screen and (max-height: 450px) {
    .overlay a {font-size: 20px}
    .overlay .closebtn {
    font-size: 40px;
    top: 15px;
    right: 35px;
    }
  }

.dark {
    color: white !important;
    background-color: rgba(159, 243, 156, 0.568) !important;
    transition: background-color 1s;
    /*padding-top: 20px;*/
}

/* Index stylings */
.welcome-sect{
    background-image:linear-gradient(
        to right bottom,
         hsl(120, 1%, 26%),
        rgba(96, 97, 97, 0.432) ),
    url(/assets/home.JPG);
    /* background: url(../images/home.JPG); */
    background-size: cover;
    background-repeat: no-repeat;
    background-position: top;
    height: 100vh;
    /* clip-path: polygon(0 0, 100% 0, 100% 85vh, 0 100%) */
}

.welcome-contents{
    padding-top: 40vh;
}
.welcome-btn{
    display: block;
    text-align: center;
    /* background-color: #fff; */
    border: 1px solid white;
    border-radius: 20px 20px;
    width: 50%;
    padding: 7px;
    margin: 7px;
    font-size: 20px;
    text-decoration: none !important;
    color: white;
}
.welcome-btn:hover{
    background-color: white;
    color: #777;
}

.welcome-carousel{
    padding-top: 10vh;
}
.carousel-text{
    text-align: center;
    display: block;
    color: white;
    font-weight: 700;
    font-size: 40px;
}

/* this is the styling for the about page */
.about-welcome-sect{
    background-image:linear-gradient(
        to right bottom,
         hsl(120, 1%, 26%),
          rgba(96, 97, 97, 0.432) ),
    url('/assets/home.JPG');
    background-size: cover;
    background-repeat: no-repeat;
    background-position: top;
    height: 100vh;
    clip-path: polygon(0 0, 100% 0, 100% 85vh, 0 100%)
}
.about-welcome-sect > h1{
    color: white;
    font-size: 15vh;
    padding-top: 20vh;
    padding-bottom: 30vh;
    text-align: center;
    font-family: 'Pacifico', cursive !important;
}
.container > h5{
    color: white;
    font-size: 9vh;
    padding-top: 10vh;
    padding-bottom: 5vh;
    text-align: center;
    font-family: 'Pacifico', cursive !important;
}
/* .buttons{
    position: absolute;
    margin-top: -30vh;
} */
.card{
    border: none !important;
}
.card-title{
    font-size: 40px !important;
    text-decoration: underline;
    text-decoration-color: red;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    font-weight: bolder;
}
#card-text {
    font-size: 20px !important;
    /* text-align: start !important; */
    font-family: monospace;
}
.about-info > p {
    font-size: 20px;
    text-align: start !important;
}
.title-s {
    font-weight: bolder;
}
.skill-mf > p{
    font-size: 30px !important;
}
.skill-mf > span {
    font-size: 20px;
}
.title-ss{
    font-weight: bolder;
    text-decoration-line: underline;
    text-decoration-color: red;
}
.skill-mf > span {
    font-weight: bolder !important;
}
.fa{
    color: white !important;
    font-size: 25px !important;
}
td{
    font-size: 2.5vh;
}
th{
    font-size: 3vh;
}

/* this is the styling for the project page */

.nav-link{
    color: white !important;
}
.navbar-brand{
    font-size: 20px !important;
    font-weight: bolder !important;
}
.icon{
    color: white !important;
    background-color: white !important;
}
.nav-link:hover{
    transition: 1s ;
    border-bottom: 3px solid red;
}
.active-now{
    color: rgb(15, 231, 15) !important;
}
.card-project{
    border-left: 20px solid green !important;
}
small{
    font-size: 20px !important;
    font-weight: lighter !important;
    color: rgba(0, 0, 0, 0.397);
}
footer{
    font-size: 2vh;
}
.resume{
    color: red !important;
}
</style>
