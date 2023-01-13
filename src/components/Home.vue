<template>
  <section id="home"></section>
  <div class="landing-img">
      <div class="nav-container">
        <ul class="nav p-2">
          <li class="nav-item">
            <li><a href="#home" class="btn gap-5 text-light" style="font-size: large;">Home</a></li>
          </li>
          <li class="nav-item">
            <li><a href="#about" class="btn gap-5 text-light" style="font-size: large;" >About</a></li>
          </li>
          <li class="nav-item">
            <li><a href="#resume" class="btn gap-5 text-light" style="font-size: large;">Resume</a></li>
          </li>
          <li class="nav-item">
            <li><a href="#projects" class="btn gap-5 text-light" style="font-size: large;">Projects</a></li>
          </li>
          <li class="nav-item">
            <li><a href="#testimonials" class="btn gap-5 text-light" style="font-size: large;">Testimonials</a></li>
          </li>
          <li class="nav-item">
            <li><a href="#contact" class="btn gap-5 text-light" style="font-size: large;">Contact</a></li>
          </li>
        </ul>
      </div>
    <header>
  <div class="display-left text-dark" style="padding-left:50px;padding-bottom:50px;">
    <img class="spin" src="https://i.postimg.cc/0jWp1JRy/My-project.png" alt="">
    <h1>Welcome to my Portfolio</h1><br>
   
      <div class="typewriter">
        <h4>Aspiring Web Developer</h4>
      </div>
    <br>
    <p><button><a href="#about">Get to know me</a></button></p>
    <div class="btn-group" role="group" aria-label="Basic outlined example">
      <a class="btn btn-lg btn-floating text-dark" href="https://www.instagram.com/meezaan.davids/" target="_blank" role="button"><i class="fab fa-instagram"></i></a>
      <a class="btn btn-lg btn-floating text-dark" href="https://twitter.com/DavidsMeezaan" target="_blank" role="button"><i class="fab fa-twitter"></i> </a>
      <a class="btn btn-lg btn-floating text-dark" href="https://www.youtube.com/channel/UCLn6kcbWaK1e_NpKx8OX9bg" target="_blank" role="button"><i class="fab fa-youtube"></i></a>
    </div>

  </div>
</header>
  </div>
</template>
<script>
export default {
  name: 'Home',
}
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Dancing+Script&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Dancing+Script&family=Raleway:wght@100&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@300&display=swap');

#home {
  height: 100%;
  width: 100%;
}
.spin {
  height:90px;
  width:90px;
}

h1 {
  font-family: 'Raleway', sans-serif;
}

h5 {
  font-family: 'Quicksand', sans-serif;
}

li {
  display: inline-flex;
  list-style: none;
}

header {
  position: relative;
  top: 40%;
  color: white;
}

button {
  background-color: transparent;
  height: 30px;
  border-radius: 5px;
  border: none;
  font-family: 'Dancing Script', cursive;
  font-size: larger;
}

button:hover {
  background-color: rgb(216, 191, 191);
  color: black;
}

a:link {
  text-decoration: none;
  color: black;
}

a:visited {
  text-decoration: none;
}

a:hover {
  text-decoration: none;
}

a:active {
  text-decoration: none;
}
.nav-container {
  width: 100%;
  text-align: center;
}
.container{
    width: 350px;
    padding: 30px 30px 50px;
    background-color: transparent;
    border-radius: 10px;
    color: white;
    position: relative;
    top: 20%;
}
.icon {
  height: 300px;
  width: 100%;
}
.landing-img {
  background-image: url("https://i.postimg.cc/x8wRcZtb/landing.jpg");
  height: 100vh;
  overflow: hidden;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
  width: 100%;
}
*{
  margin: 0;
  padding: 0;
}

.spin {
  animation: rotation 8s infinite linear;
}

@keyframes rotation {
  from {
    transform: rotate(359deg);
  }
  to {
    transform: rotate(0);
  }
}

.typewriter {
	width: 34ch;
	white-space: nowrap;
	overflow: hidden;
	border-right: 4px solid #212121;
	animation: cursor 1s step-start infinite, 
    text 5s steps(18) alternate infinite;
}

@keyframes cursor {
	0%, 100% { 
    border-color: #212121; 
  }
}

@keyframes text {
	0% { 
    width: 0; 
  }
	100% { 
    width: 34ch; 
  }
}
</style>