<template>
  <div>
    <section class="hero" id="home">
      <div class="content flex-column d-flex justify-content-end">
        <div
          class="d-flex flex-column justify-content-center align-items-center"
          style="margin-bottom: 0em"
        >
          <h3 class="text-light fw-bold text-center">
            PLAY AND LEARN ABOUT DAGOHOY AND THE LONGEST REBELLION IN THE
            PHILIPPINES
          </h3>
          <div class="downloads text-light row">
            <a
              class="btn-dl col bg-black"
              target="_blank"
              href="https://drive.google.com/u/0/uc?export=download&confirm=J-Ue&id=1aJoCzor-lsmTSuOYFH98uNQJ8-51vbgh"
            >
              <img class="icon" src="../assets/windows.png" alt="" />
              Windows
            </a>
            <a
              class="btn-dl col bg-black"
              target="_blank"
              href="https://drive.google.com/u/0/uc?export=download&confirm=WyKC&id=1JIAoJmbQWb3v95E3EdX2fMLNCOMgwmME"
            >
              <img class="icon" src="../assets/android.png" alt="" />
              Android
            </a>
          </div>
        </div>

        <div
          class="bar bg-black"
          style="height: 1em; margin-bottom: -5em; margin-top: 5em"
        ></div>

        <div
          class="d-flex justify-content-between align-items-end"
          style="height: 5em"
        >
          <div class="qr">
            <img src="../assets/qr.png" />
          </div>

          <a href="#trailer">
            <img
              src="https://media.giphy.com/media/Wtg8Bmgul1Qxc0otod/source.gif"
              class="arrow_btn"
              width="100px"
              height="100px"
              style="margin-bottom: -1em"
            />
          </a>

          <img src="../assets/edge.png" class="edge" />
        </div>
      </div>
    </section>

    <!-- <section class="trailer" id="trailer">
      <div
        class="content pt-5 flex-column d-flex justify-content-between"
        id="trailer"
      >
        <h1 class="text-black my-3 fw-bolder">GAME TRAILER</h1>

        <div class="video">
          <div class="box">
            <iframe
              width="800"
              height="440"
              src="https://www.youtube.com/embed/efpjHXmZAOo"
              title="Dagohoy's Revolt Trailer"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
            ></iframe>
          </div>
        </div>

        <div>
          <a href="#overview">
            <img
              src="https://media.giphy.com/media/Wtg8Bmgul1Qxc0otod/source.gif"
              class="arrow_btn"
              width="100px"
              height="100px"
              style="margin-bottom: -2em"
            />
          </a>
          <div class="bg-black" style="height: 1em"></div>
        </div>
      </div>
    </section> -->

    <section class="overview" id="trailer">
      <div class="content flex-column d-flex justify-content-between">
        <div class="media d-flex justify-content-center">
          <div class="row" style="width: 90vw">
            <h1 class="text-dark pt-5 fw-bold">GAME TRAILER AND SCREENSHOTS</h1>

            <div class="col">
              <div class="box">
                <iframe
                  class="shadow"
                  src="https://www.youtube.com/embed/efpjHXmZAOo"
                  title="Dagohoy's Revolt Trailer"
                  frameborder="0"
                  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                  allowfullscreen
                ></iframe>
              </div>
            </div>
            <div class="col">
              <div
                class="row mx-auto justify-content-center align-items-center"
              >
                <div class="ss d-flex flex-column align-items-center mx-2 mb-1">
                  <img
                    src="../assets/ss4.png"
                    class="outline shadow"
                    style="width: inherit"
                  />
                  <p class="p-0 m-0 mt-1 fw-bold text-black">STORY</p>
                </div>
                <div class="ss d-flex flex-column align-items-center mx-2 mb-1">
                  <img
                    src="../assets/ss3.png"
                    class="outline shadow"
                    style="width: inherit"
                  />
                  <p class="p-0 m-0 mt-1 fw-bold text-black">
                    OBJECTIVES
                  </p>
                </div>
                <div class="ss d-flex flex-column align-items-center mx-2 mb-1">
                  <img
                    src="../assets/ss2.png"
                    class="outline shadow"
                    style="width: inherit"
                  />
                  <p class="p-0 m-0 mt-1 fw-bold text-black">COMBAT</p>
                </div>
                <div class="ss d-flex flex-column align-items-center mx-2 mb-1">
                  <img
                    src="../assets/ss1.png"
                    class="outline shadow"
                    style="width: inherit"
                  />
                  <p class="p-0 m-0 mt-1 fw-bold text-black">PUZZLE</p>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="polygons">
          <div class="d-flex justify-content-between align-items-end">
            <div>
              <img
                class="hm"
                src="../assets/trapezoid.png"
                style="width: 6em"
              />
              <img
                class="hm mx-2 mb-1"
                src="../assets/trapezoid.png"
                style="width: 5em               
              -webkit-transform: scaleX(-1) scaleY(-1);
              transform: scaleX(-1) scaleY(-1);"
              />
              <img class="" src="../assets/trapezoid.png" style="width: 6em" />
            </div>

            <img
              class="edge-trap"
              src="../assets/trapezoid-half.png"
              style="
                -webkit-transform: scaleX(-1) scaleY(-1);
                transform: scaleX(-1) scaleY(-1);
                margin-bottom: -1em;
              "
            />
          </div>
          <div class="bg-black" style="height: 1em"></div>
        </div>
      </div>
    </section>

    <div class="footer bg-black pt-3 text-light">
      <div class="sites align-items-center">
        <a
          class="mx-3 align-items-center"
          target="_blank"
          href="https://soncraft.netlify.app"
        >
          <img class="icon" src="../assets/soncraft-logo.png" alt="" />
          SONCRAFT</a
        >
        <a
          class="mx-3 align-items-center"
          target="_blank"
          href="https://soncraft.itch.io"
        >
          <img
            class="icon"
            src="https://samirgeorgy.files.wordpress.com/2020/01/itchio-textless-icon.png"
            alt=""
          />
          SONCRAFT.ITCH.IO</a
        >
      </div>
      <div class="text d-flex mt-3 justify-content-center">
        <p class="text-center">
          Dagohoy's Revolt 3D Educational Game &#169; SECRET CLASS, 2022
          Capstone Project. <br />
          This game is made to promote and Distribute knowledge about the
          longest rebellion in the Philippines led by the Boholano hero
          Francisco Sendrijas also known as Dagohoy.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "HomeView",
};
</script>

<style scoped>
a {
  text-decoration: none;
  color: #fff;
}

.downloads {
  width: 35em;
}
.btn-dl {
  border-radius: 5px;
  border: rgb(187, 187, 187) solid 1px;
  font-size: 2.2em;
  margin: 0.5em;
  padding: 0.2em;
}
.btn-dl .icon {
  width: 40px;
}

a:hover {
  color: #fff;
}
section,
.content {
  height: 100vh;
}

.arrow_btn {
  cursor: pointer;
  width: 150px;
  height: 70px;
  background-image: url("../assets/trapezoid.png");
  background-size: contain;
  background-repeat: no-repeat;
  padding-left: 30px;
  padding-right: 30px;
}

.hero {
  background-image: url("../assets/game-bg.png");
  background-size: cover;
  background-repeat: no-repeat;
}

.hero h3 {
  color: white;
  text-shadow: 2px 2px 4px #000000;
  font-size: 3em;
  width: 50vw;
}
.qr {
  width: 10em;
  padding: 2em;
}
.qr img {
  width: 10em;
}
.edge {
  width: 10em;
}

.trailer {
  background-color: #fff;
  background-image: url("../assets/pattern4.jpg");
  background-size: cover;
  background-repeat: no-repeat;
}
.overview {
  background-color: #ffffff;
  background-image: url("../assets/pattern2.jpg");
  background-size: cover;
  background-repeat: no-repeat;
}

.media h1 {
  margin-top: 2em;
  margin-bottom: 1em;
  font-size: 4em;
}

.ss {
  width: 22em;
}
.ss p{
  font-size: 1.5em;
}
.outline {
  outline: #000000 2px solid;
}
.shadow {
  box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px,
    rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px,
    rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;
}
iframe {
  outline: #000000 2px solid;
  width: 750px;
  height: 450px;
}

.footer .text p {
  width: 50vw;
}
.icon {
  width: 20px;
  margin-bottom: 2px;
}
.edge-trap {
  width: 15em;
}
@media screen and (max-width: 1600px) {
  iframe {
    width: 500px;
    height: 320px;
  }
  .media h1 {
    margin-top: 1em;
    margin-bottom: 1em;
    font-size: 2.5em;
  }
  .ss {
    width: 15em;
  }
  .ss p{
  font-size: 1.2em;
}
  .qr,
  .edge {
    width: 7em;
  }
  .qr img {
    width: 7em;
  }
  .hero h3 {
    font-size: 2em;
  }

  .downloads {
    width: 25em;
  }
  .btn-dl {
    font-size: 1.5em;
    margin: 0.5em;
    padding: 0.2em;
  }
  .btn-dl .icon {
    width: 20px;
  }
}

@media screen and (max-width: 600px) {
  .hm {
    display: none;
  }
  .qr img {
    display: none;
  }
  .hero h3 {
    font-size: 1.6em;
    width: 90vw;
  }
  .downloads {
    width: 15em;
    margin-bottom: 3em;
  }
  .btn-dl {
    margin: 0.1em;
    padding-left: 2em;
    padding-right: 2em;
  }

  .media h1 {
    margin-top: 2em;
    margin-bottom: 1em;
    font-size: 1.5em;
  }

  iframe {
    width: 300px;
    height: 180px;
    margin-bottom: 1em;
  }
  .ss {
    width: 8em;
  }
  .footer .text p {
    width: 90vw;
    font-size: 0.75em;
  }
  .edge-trap {
    width: 10em;
  }
  .hero {
    background-image: url("../assets/game-bg-mobile.png");
  }
}
</style>
