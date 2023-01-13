<template>
  <div id="about">
  <NavBar/>
  <center>
    <div class="btn-group p-2" role="group" aria-label="Basic outlined example">
    <a href="#home" type="button" class="btn btn-outline-dark"><i class="fa-solid fa-arrow-up"></i></a>
    <a href="#resume" type="button" class="btn btn-outline-dark"><i class="fa-solid fa-arrow-down"></i></a>
  </div>
  </center>
  <body>
      <div>
        <h2>About</h2>
        <div class="container">
          <div class="wrapper">
              <div class="text-box">
                <div class="container-img">
                  <img src="https://i.postimg.cc/tRftwSZW/Meezaan.jpg" class="image" style="height: 80vh;" alt="">
                  <div class="middle">
                    <div class="text">Meezaan Davids</div>
                   </div>
                  </div>
                  <h2>About Me</h2>
                  <p>Hello, my name is Meezaan Davids I am 19 years old, and I was born in Cape Town South Africa. I would like to think I am a genuine straight forward person. I am very interested in learning new skills, whether it is cooking or coding I am very much interested in it. I would also like to consider myself a very passionate sports fan. I try to keep up to date with all my sports. I am really interested in a possible career in web design. At this point in my life I am very into learning new things because new experiences bring new opportunities.</p>
                  <div class="col">
                      <h3>Profile</h3>
                      <ul>
                          <li><b>FullName:</b>  Meezaan Davids</li>
                          <li><b>D.O.B:</b> 24/05/03</li>
                          <li><b>Gender:</b> Male</li>
                          <li><b>Citizenship:</b> South African</li>
                      </ul>
                    </div>
                    <div class="btn-group">
                      <a download href="@/assets/CV.png" class="btn btn-dark">Download CV</a>
                      <a href="#contact" class="btn btn-dark">Want to know more</a>
                    </div>
              </div>
        </div>
       </div>
      </div>
  </body>
  </div>
</template>
<script>
import NavBar from '@/components/NavBar.vue'
export default {
  name: 'About',
  components: {
      NavBar
  }
}
</script>
<style scoped>
#about {
  height: 100%;
  width: 100%;
  background-image: linear-gradient(white, rgb(216, 191, 191));
  color:black
}
body {
  display: flex;
  justify-content: center;
  align-items: center;
  align-items: center;
}
h1 {
  text-align: center;
}
img {
  max-width: 500px;
  height: 450px;
  float: left;
  margin-right: 20px;
  width: 100%;
}
.wrapper {
  margin: 150px auto;
  width: 90%;
}
li {
  list-style: none;
}
.container{
  width: 100%;
  padding: 30px 30px 50px;
  background-color: transparent;
  border: 2px solid rgba(255,255,255,0.06);
  border-radius: 10px;
  box-shadow: 0 20px 30px rgba(0,0,0,0.2);
  backdrop-filter: blur(10px);
  height: auto;
}
.image {
opacity: 1;
display: block;
width: 100%;
height: auto;
transition: .5s ease;
backface-visibility: hidden;
}
.middle {
transition: .5s ease;
opacity: 0;
position: absolute;
top: 60%;
left: 27%;
transform: translate(-50%, -50%);
-ms-transform: translate(-50%, -50%);
text-align: center;
}
.container-img:hover .image {
opacity: 0.7;
}
.container-img:hover .middle {
opacity: 1;
}
.text {
background-color:rgb(216, 191, 191);
color: black;
font-size: 16px;
padding:6px;
border: 2px solid white;
}
</style>