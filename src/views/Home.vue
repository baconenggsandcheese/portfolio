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
  </main>
</template>

<script>
import one from "@/components/one.vue";
import two from "@/components/two.vue";
import three from "@/components/three.vue";
export default {
  components: {
    one,
    two,
    three,
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
  display: flex;
  justify-content: center;
  align-items: center;
  scroll-snap-align: center;
}
.c-section--1 {
  background-color: black;
}
.c-section--2 {
  /* background-color: var(--color-2);
  color: var(--color-2); */
  background-color: red;
}
.c-section--3 {
  /* background-color: var(--color-3);
  color: var(--color-3); */
  background-color: blue;
}

.c-section--title {
  font-size: 6rem;
  filter: invert(1);
}
</style>
