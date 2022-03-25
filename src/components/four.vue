<template>
  <div class="fourmain">
    <br />
    <br />
    <div class="logos">
      <div class="vue">
        <img src="@/assets/vuelogo.png" />
        VueJs
        <div class="info">
          <i>(The same framework this website was made with)</i>
        </div>
      </div>
      <div class="react">
        <img src="@/assets/reactlogo.png" />
        ReactJs
        <div class="info">
          <i>(Created a project called Toolshed with this)</i>
        </div>
      </div>
      <div class="python">
        <img src="@/assets/pythonlogo.png" />
        Python
        <div class="info">
          <i>(Mainly use to create a lot of features)</i>
        </div>
      </div>
      <div class="cpp">
        <img class="c" src="@/assets/cpluspluslogo.png" />
        C++
        <div class="info">
          <i>(My First programming Language)</i>
        </div>
      </div>
      <div class="tss">
        <img class="ts" src="@/assets/tslogo.png" />
        TypeScript
        <div class="info">
          <i>(I use to create a lot of featues)</i>
        </div>
      </div>
    </div>
  </div>
</template>

<script></script>

<style scoped>
.fourmain {
  margin-left: 20px;
}
img {
  height: 1em;
}
.logos {
  font-size: 45px;
  font-family: "Cartograph CF";
  display: grid;
  grid-template-columns: auto;
  grid-template-rows: auto;
  row-gap: 0.7em;
  align-items: center;
  justify-content: center;
  text-align: center;
}
.info {
  font-size: 20px;
  color: #ff4433;
}
</style>
