<template>
    <div id="header " class="about-welcome-sect">
    <div >
        <!-- the navbar begins here -->
        <nav class="navbar navbar-expand-lg navbar-dark px-4">
                <router-link to="/HomePage"><li class="navbar-brand text-white" >MFONIDO-MARK</li></router-link>
            <button class="navbar-toggler " type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon "></span>
            </button>
            <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
                    <ul class="navbar-nav">
                        <li class="nav-item px-2">
                            <router-link to="/AboutMe" class="nav-link" >About <span class="sr-only">(current)</span></router-link>
                        </li>
                        <li class="nav-item active px-2">
                            <router-link to="/MyProjects" class="nav-link">Projects<span class="sr-only">(current)</span></router-link>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link resume" href="assets/Resume.pdf">Resume</a>
                        </li>
                    </ul>
            </div>
        </nav>
        <!-- navbar ends here -->
        <h1 class="text-center text-white pt-4">GET-IN-TOUCH</h1>
<div>
                    <form action="POST" data-netlify="true" class="text-white">
                        <div class="form-group">
                            <label for="formGroupExampleInput">NAME</label>
                            <input type="text" class="form-control" placeholder="" name="name" required>
                        </div>
                        <div class="form-group">
                            <label for="formGroupExampleInput2">EMAIL</label>
                            <input type="email" class="form-control" id="inputEmail4" name="email" required>
                        </div>
                        <div class="form-group">
                            <label for="exampleFormControlTextarea1">Your Message</label>
                            <textarea class="form-control" id="exampleFormControlTextarea1" rows="3" name="message"
                                required></textarea>
                        </div>
                        <button type="submit" value="send message" class="btn btn-primary">Submit</button>
                    </form>

                    <!-- social links -->

</div>
<div class="social-links px-4">
    <div class="my-3">
        <a title="LinkedIn" href="https://www.linkedin.com/in/mfonido-mark-4baa42120/" target="_blank">
                            <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="25" height="25"
                                viewBox="0 0 172 172" style=" fill:#000000; opacity: .9;">
                                <g fill="none" fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt"
                                    stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray=""
                                    stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none"
                                    text-anchor="none" style="mix-blend-mode: normal">
                                    <path d="M0,172v-172h172v172z" fill="none"></path>
                                    <g fill="#ffffff">
                                        <path
                                            d="M141.04,13.76h-110.08c-9.4944,0 -17.2,7.7056 -17.2,17.2v110.08c0,9.4944 7.7056,17.2 17.2,17.2h110.08c9.4944,0 17.2,-7.7056 17.2,-17.2v-110.08c0,-9.4944 -7.7056,-17.2 -17.2,-17.2zM58.48,
                                                    68.8v65.36h-20.64v-65.36zM37.84,49.7768c0,-4.816 4.128,-8.4968 10.32,-8.4968c6.192,0 10.0792,3.6808 10.32,8.4968c0,4.816 -3.8528,8.7032 -10.32,
                                                    8.7032c-6.192,0 -10.32,-3.8872 -10.32,-8.7032zM134.16,134.16h-20.64c0,0 0,-31.8544 0,-34.4c0,-6.88 -3.44,-13.76 -12.04,-13.8976h-0.2752c-8.3248,0 -11.7648,7.0864 -11.7648,13.8976c0,3.1304 0,34.4 0,
                                                    34.4h-20.64v-65.36h20.64v8.8064c0,0 6.6392,-8.8064 19.9864,-8.8064c13.6568,0 24.7336,9.3912 24.7336,28.4144z">
                                        </path>
                                    </g>
                                </g>
                            </svg>
                        </a>
    </div>
    <div class="my-3">
        <a title="Twitter" href="https://twitter.com/MfonidoMark" target="_blank">
                            <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="25" height="25"
                                viewBox="0 0 172 172" style=" fill:#000000; opacity: .9;">
                                <g fill="none" fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt"
                                    stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray=""
                                    stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none"
                                    text-anchor="none" style="mix-blend-mode: normal">
                                    <path d="M0,172v-172h172v172z" fill="none"></path>
                                    <g fill="#ffffff">
                                        <path
                                            d="M172.215,35.905c-6.35594,2.82188 -13.16875,4.71656 -20.33094,5.57656c7.31,-4.38063 12.92687,-11.31438 15.56062,
                                                    -19.565c-6.82625,4.04469 -14.41844,6.9875 -22.4675,8.57312c-6.45,-6.88 -15.64125,-11.16656 -25.81344,-11.16656c-19.53812,
                                                    0 -35.38094,15.82937 -35.38094,35.3675c0,2.76812 0.3225,5.46906 0.92719,8.0625c-29.40125,-1.47813 -55.45656,-15.56063 -72.91187,-36.96656c-3.05031,5.24062 -4.78375,11.31437 -4.78375,17.79125c0,12.26844 6.235,23.09906 15.73531,29.455c-5.805,-0.18813 -11.26062,-1.78719 -16.03094,
                                                    -4.43438c0,0.14781 0,0.29563 0,0.44344c0,17.14625 12.20125,31.43031 28.36656,34.69562c-2.95625,0.80625 -6.08719,
                                                    1.23625 -9.31219,1.23625c-2.28438,0 -4.50156,-0.215 -6.665,-0.645c4.515,14.04219 17.57625,24.295 33.04281,24.57719c-12.09375,9.48688 -27.34531,15.13063 -43.92719,15.13063c-2.86219,0 -5.67062,-0.16125 -8.42531,-0.49719c15.64125,10.05125 34.23875,15.89656 54.22031,15.89656c65.06438,
                                                    0 100.64688,-53.89781 100.64688,-100.63344c0,-1.53187 -0.04031,
                                                    -3.07719 -0.09406,-4.58219c6.90687,-4.98531 12.9,-11.22031 17.64344,-18.31531z">
                                        </path>
                                    </g>
                                </g>
                            </svg>
                        </a>
    </div >
    <div class="py-3">
        <a title="GitHub" href="https://github.com/favourmark05" target="_blank">
                            <i class="fa fa-github" aria-hidden="true"></i>
                        </a>
    </div>
</div>
    </div>

    <!-- <footer>
        <div class="col text-center bg-dark text-white"> © 2020 Copyright: Mfonido Mark</div>
    </footer> -->
    </div>
</template>

<style scoped>
.nav-link:hover{
    transition: 1s ;
    border-bottom: 3px solid red;
}
.fa-github{
    color: white;
    font-size: 30px;
}
html{
    box-sizing: border-box;
    font-size: 62.5%;
    scroll-behavior: smooth;

}

*::before{
    margin: 0;
    padding: 0;
    box-sizing: inherit;
    overflow: hidden;
}
.about-welcome-sect{
    background-image:linear-gradient(
        to right bottom,
         hsl(120, 1%, 26%),
          rgba(96, 97, 97, 0.432) ),
    url('/assets/home.JPG');
    background-size: cover;
    background-repeat: no-repeat;
    background-position: top;
    height:115vh;
    /* clip-path: polygon(0 0, 100% 0, 100% 98vh, 0 100%) */
}
@media screen and (max-height: 600px){
    .about-welcome-sect{
        height: 135vh;
    }
}

  form{
    box-sizing: border-box;
    width: 100%;
    padding: 8px;
    /* border: 5px solid #ccc; */
    /* border-radius: 20px; */
    /* box-shadow: 0 5px 5px #aaa; */
    margin: 10px;
    /* align-content: center; */
    display: flex;
    flex-flow: column;
    align-items: center;
    /* padding: 30px; */
  }
  .social-links{
      display: grid;
      grid-template-rows: auto auto auto;
  }

/* .container{
    max-height: fit-content !important;
    max-width: 700px !important;
} */
</style>
