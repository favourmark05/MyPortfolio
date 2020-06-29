<template>
  <div class="body">
<header id="header">
        <div class="container-fluid welcome-sect">
            <div class="row welcome-text-box">
                <div class="col-md-12">
                    <a href="index.html" class="navbar-brand Mark float-left active-now">MFONIDO MARK</a>
                    <span class="open-nav" style="font-size:30px;cursor:pointer;color: white;"
                        @click="openNav()">&#9776;</span>

                    <!-- Overlay Navigation -->
                    <div id="myNav" class="overlay">
                        <a href="javascript:void(0)" class="closebtn" @click="closeNav()">&times;</a>
                        <div class="overlay-content">
                            <router-link to="/AboutMe" >AboutMe</router-link>
                            <router-link to="/MyProjects" >Explore Project</router-link>
                            <router-link to="/ContactMe" >Say Hello</router-link>
                        </div>
                    </div>
                </div>
            </div>
            <!-- Welcome-text-contents -->
            <div class="row  welcome-contents">
                <div class="col-md-6">
                    <!-- <a href="about.html" class="welcome-btn ">About Me</a> -->
                    <router-link to="/AboutMe" class="welcome-btn">AboutMe</router-link>
                    <router-link to="/MyProjects" class="welcome-btn">Explore Project</router-link>
                    <router-link to="/ContactMe" class="welcome-btn">Say Hello</router-link>
                </div>

                <div class="col-md-6 welcome-carousel">
                    <!-- Carousel part -->
                    <div id="carouselExampleFade" class="carousel slide carousel-fade" data-ride="carousel">
                        <div class="carousel-inner">
                            <div class="carousel-item active">
                                <!-- <img src="..." class="d-block w-100" alt="..."> -->
                                <h1 class="carousel-text">I am <br> MFONIDO MARK</h1>
                            </div>
                            <div class="carousel-item">
                                <!-- <img src="..." class="d-block w-100" alt="..."> -->
                                <h1 class="carousel-text">FRONT-END DEVELOPER</h1>
                            </div>
                            <div class="carousel-item">
                                <!-- <img src="..." class="d-block w-100" alt="..."> -->
                                <h1 class="carousel-text">GRAPHICS DESIGNER</h1>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </header>
  </div>
</template>

<script>
export default {
  methods: {
    openNav () {
      document.getElementById('myNav').style.width = '100%'
    },
    closeNav () {
      document.getElementById('myNav').style.width = '0%'
    }
  }
}
</script >

<style scoped>
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
/* a,a::after, */
a::before, a:link{
    text-decoration: none;
    color: white;
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
    height: 100vh;
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
  .welcome-sect{
    background-image:linear-gradient(
        to right bottom,
         hsl(120, 1%, 26%),
          rgba(96, 97, 97, 0.432) ),
    url('/assets/home.JPG');
    /* background-image: url(/assests/index.JPG); */
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

</style>
