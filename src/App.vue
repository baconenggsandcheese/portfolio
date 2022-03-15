<template>
  <div class="appmain">
    <logo> </logo>
    <!-- <div id="navbar">
      <router-link to="/" id="home">
        <img
          id="home"
          src="https://img.icons8.com/external-flaticons-lineal-color-flat-icons/64/000000/external-portfolio-creativity-flaticons-lineal-color-flat-icons.png"
        />
      </router-link>
      <router-link to="/merch">
        <img
          id="merch"
          src="https://img.icons8.com/external-tone-royyan-wijaya/64/000000/external-cart-ecommerce-bram-bram-tone-royyan-wijaya-3.png"
        />
      </router-link>
    </div> -->
    <hr />
    <router-view />
  </div>
</template>

<script></script>

<style type="scss">
/* Restting CSS  */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
/*Styles which are gonna be same for the whole project*/
html {
  /* background-color: #ffefe0; */
  /* background-image: url("./assets/background.png"); */
  overflow-x: hidden;
  overflow-y: hidden;
}
/* Styles for the links */
a {
  text-decoration: none;
}
#navbar {
  text-align: center;
  background-color: #ffefe0;
  /* background-color: rgba(255,255,255,0.5); */
}
#home {
  height: 30px;
  margin-right: 10px;
}
#merch {
  height: 30px;
  margin-right: 10px;
}
#about {
  font-family: "Cartograph CF";
  font-size: 30px;
}
/* Enrty animation */
.animate {
  animation-duration: 0.75s;
  animation-name: animate-fade;
  animation-delay: 0.75s;
  animation-fill-mode: backwards;
}
    
@keyframes animate-fade {
    0% { opacity: 0; }
  100% { opacity: 1; }
}


.animate.pop {
  animation-name: animate-pop;
  animation-timing-function: cubic-bezier(.26,.53,.74,1.48);
}

@keyframes animate-pop {
  0% {
    opacity: 0;
    transform: scale(0.5, 0.5);
  }
        
  100% {
    opacity: 1;
    transform: scale(1, 1);
  }
}


.delay-1 {
  animation-delay: 0.66s;
}
    
.delay-2 {
  animation-delay: 0.77s;
}
    
.delay-3 {
  animation-delay: 0.88s;
}
.delay-4 {
  animation-delay: 1.5s;
}
</style>
