<template>
  <div class="fourmain">
    <br />
    <br />
    <div class="logos">
      <div class="vue">
        <img src="@/assets/vuelogo.png" />
        VueJs
        <div class="info">
          <i>(The same thing this website was made with)</i>
        </div>
      </div>
      <div class="react">
        <img src="@/assets/reactlogo.png" />
        React
      </div>
      <div class="python">
        <img src="@/assets/pythonlogo.png" />
        Python
      </div>
      <div class="cpp">
        <img class="c" src="@/assets/cpluspluslogo.png" />
        C++
      </div>
      <div class="tss">
        <img class="ts" src="@/assets/tslogo.png" />
        TypeScript
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
  font-size: 55px;
  font-family: "Cartograph CF";
  display: grid;
  grid-template-columns: auto;
  grid-template-rows: auto;
  row-gap: 1.2em;
}
.info {
  font-size: 20px;
}
</style>
