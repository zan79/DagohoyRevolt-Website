<template>
  <NavBar />
  <router-view class="" />
  <CarouselCon
    :slides="slides"
    :interval="2000"
    controls
    indicators
  ></CarouselCon>
</template>

<script>
import NavBar from "@/components/NavBar.vue";

export default {
  components: { NavBar },
  setup() {},
};
</script>

<style>
#app {
  font-family: Kanit, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 0;
  padding: 0;
  box-sizing: border-box;

}
</style>
