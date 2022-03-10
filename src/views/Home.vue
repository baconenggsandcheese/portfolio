<template>
  <main class="c-main">
    <section>
      <div class="c-section c-section--1">
        <p class="c-section--title">
          <one />
        </p>
      </div>
    </section>
    <section>
      <div class="c-section c-section--2">
        <p class="c-section--title">
          <two />
        </p>
      </div>
    </section>
    <section>
      <div class="c-section c-section--3">
        <p class="c-section--title">
          <three />
        </p>
      </div>
    </section>
    <section>
      <div class="c-section c-section--4">
        <p class="c-section--title">
          <four />
        </p>
      </div>
    </section>
    <section>
      <div class="c-section c-section--5">
        <p class="c-section--title">
          <five />
        </p>
      </div>
    </section>
    <section>
      <div class="c-section c-section--5">
        <p class="c-section--title">
          <six />
        </p>
      </div>
    </section>
  </main>
</template>

<script>
import one from "@/components/one.vue";
import two from "@/components/two.vue";
import three from "@/components/three.vue";
import four from "@/components/four.vue";
import five from "@/components/five.vue";
import six from "@/components/six.vue";
export default {
  components: {
    one,
    two,
    three,
    four,
    five,
    six,
  },
};
</script>

<style type="scss" scoped>
body {
  overflow: hidden;
}

/* Hide scrollbar for Chrome, Safari and Opera */
.c-main::-webkit-scrollbar {
  display: none;
}

/* Hide scrollbar for IE, Edge and Firefox */
.c-main {
  -ms-overflow-style: none; /* IE and Edge */
  scrollbar-width: none; /* Firefox */
}

.c-main {
  padding: 0;
  margin: 0;
  width: 100%;
  height: 100vh;
  overflow-y: scroll;
  scroll-snap-points-y: repeat(100vh);
  scroll-snap-type: y mandatory; /*Enable Scroll Snap*/
}

.c-section {
  width: 100%;
  height: 100vh;
  scroll-snap-align: center;
}
.c-section--1 {
  background-color: #ffefe0;
}
.c-section--2 {
  background-color: #ffefe0;
  overflow: hidden; /*To hide text overflow */
}
.c-section--3 {
  background-color: red;
}
.c-section--4 {
  background-color: green;
}
.c-section--5 {
  background-color: yellow;
}
.c-section--5 {
  background-color: blueviolet;
}
/* Major styles for the heading */
.c-section--title {
  color: black;
}
</style>
