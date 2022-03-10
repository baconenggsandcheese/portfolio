<template>
  <div class="appmain">
    <logo> </logo>
    <div id="navbar">
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
    </div>
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
  background-color: whitesmoke;
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
</style>
