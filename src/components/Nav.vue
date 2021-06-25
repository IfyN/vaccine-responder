<template>
<nav class="nav-section">
  <h1 class="nav_title">
   <router-link to="/">Vaccine Responder</router-link>
</h1>

  <div class="nav-items">
    <router-link to="/about">About</router-link>
    <router-link to="/volunteer">Volunteer</router-link>
  </div>
  
  <!--nav class="container">
    <--div class="one">
    <a href="#" class="navLinks">Home</a>
    </div>
    <div class="two">
    <a href="#" class="navLinks">About Me</a>
    </div>
    <div class="logo">
    </div>
    <div class="three">
    <a href="#" class="navLinks">Portfolio</a>
    </div>
    <div class="four">
    <a href="#" class="navLinks">Contact Me</a>
    </div>
  </nav-->
</nav>
</template>

<style scoped>

nav.nav-section {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  width: 100%;
  /*grid-template-columns: repeat(5, 1fr);
  grid-auto-rows: auto;
  gap: 1em;
  align-items: center;
  text-align: center;
  border-bottom: 4px solid black;
  background: green;*/
}

.nav-items{
  display: flex;
 flex-direction: row;
 justify-content: space-around;
}



/*@media screen and (max-width: 900px) {
  nav {
    grid-template-columns: 100%;
    grid-template-rows: auto;
    gap: 1em;
 }
}  

h1{
  text-align: center;
}

.one {
  grid-column: 1;
}

.two {
  grid-column: 2;
}

.logo {
  grid-column: 3;
  background-image: url("https://blog.codepen.io/wp-content/uploads/2012/06/Black-Large.png");
  background-position: center;
  background-size: contain;
  background-repeat: no-repeat;
  height: 10vh;
}

.three {
  grid-column: 4;
}

.four {
  grid-column: 5;
}

.navLinks {
  font-family: 'Ubuntu', sans-serif;
  font-size: 1.2em;
  text-transform: uppercase;
  text-decoration: none;
  color: black;
}

.navLinks:hover {
  color: white;
  border-left: 1px solid white;
  border-right: 1px solid white;
  padding: 1em 1em;
}

#twist {
  color: blue;
}*/
</style>
