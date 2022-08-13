<template>
  <div class="navbar bg-black fixed-top py-2 d-flex justify-content-between">
    <div class="links d-flex justify-content-between">
      <div class="title pe-2">
        <img src="../assets/TitleArt.png" class="" />
      </div>
      <div>
        <a>&#8203;</a>
      </div>
    </div>
    <div class="menus pe-5">
      <a href="#home" class="hm mx-2">HOME</a>
      <a href="#trailer" class="hm mx-2">TRAILER</a>
    </div>
    <!-- <div class="music me-3 px-1">
      MUSIC <span class="text-success">ON</span>
    </div> -->
  </div>
</template>

<script>
export default {
  setup() {},
};
</script>

<style scoped>
a {
  text-decoration: none;
  color: #fff;
  font-size: 2em;
}
a:hover {
  color: rgb(255, 145, 0);
}
.title {
  background-image: url("../assets/trapezoid-half.png");
  background-size: contain;
  background-repeat: no-repeat;
  margin-bottom: -10em;
  text-align: center;
  width: 30em;
}
.title img {
  margin-top: 1em;
  width: 22em;
}

.music {
  color: #fff;
  border: #fff solid;
  cursor: pointer;
}

@media screen and (max-width: 1600px) {
  .title {
    width: 20em;
  }
  .title img {
    margin-top: 0.5em;
    width: 15em;
  }
  a {
    font-size: 1.2em;
  }
}

@media screen and (max-width: 600px) {
  .hm {
    display: none;
  }
  .title {
    width: 13em;
  }
  .title img {
    width: 11em;
    margin-top: -0.05em;
  }
  .navbar {
    height: 2em;
  }
}
</style>