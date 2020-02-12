<template>
  <div class="dance container-fluid">
    <div class="row headerDance">
      <div class="col-md-3">
        <img
          src="https://redtricom.files.wordpress.com/2015/02/004-andrew-weeks_-youth-and-teen-2015.jpg?w=1024&h=682"
          alt
          class="danceImg1"
        />
      </div>
      <div class="col-md-5 titleText">
        <h1>
          <span class="char1">L</span>
          <span class="char2">E</span>
          <span class="char3">T</span>
          <span class="char4">'</span>
          <span class="char5">S</span>
          &nbsp;
          <span class="char6">D</span>
          <span class="char7">A</span>
          <span class="char8">N</span>
          <span class="char9">C</span>
          <span class="char10">E</span>
          <span class="wiggle1">!!</span>
        </h1>
      </div>
      <div class="col-md-3">
        <img
          src="https://26qwi858rq21jpf4913ehms1-wpengine.netdna-ssl.com/wp-content/uploads/2017/10/Kidsdancing_1400.jpg"
          alt
          class="danceImg2"
        />
      </div>
    </div>
    <div class="row">
      <div class="col-md-8 offset-md-2"></div>
    </div>
  </div>
</template>


<script>
export default {
  name: "dance",
  data() {
    return {};
  },
  computed: {},
  methods: {},
  components: {}
};
</script>


<style scoped>
.dance {
  background-color: cornflowerblue;
  height: 90vh;
}

.headerDance {
  height: 20vh;
  justify-content: space-evenly;
}

.danceImg1 {
  height: 100%;
  width: 100%;
  border-radius: 20px;
  position: relative;
  top: 5vh;
  transform: rotate(-30deg);
}

.danceImg2 {
  height: 100%;
  width: 100%;
  border-radius: 20px;
  position: relative;
  top: 15vh;
  transform: rotate(35deg);
}

.char1 {
  color: aquamarine;
}

.char2 {
  color: yellow;
}

.char3 {
  color: blueviolet;
}

.char4 {
  color: coral;
}

.char5 {
  color: rgb(250, 185, 8);
}

.char6 {
  color: red;
}

.char7 {
  color: rgb(123, 255, 0);
}

.char8 {
  color: rgb(240, 167, 11);
}

.char9 {
  color: rgb(68, 0, 255);
}

.char10 {
  color: rgb(207, 230, 9);
}

.titleText {
  color: white;
  text-shadow: 1px 1px black;
  text-align: center;
  font-size: 6vh;
  padding-top: 5vh;
  display: flex;
  justify-content: center;
  align-items: baseline;
  font-family: "Comic Sans MS", cursive, sans-serif;
  font-weight: bold;
}

@keyframes wiggle {
  from {
    color: orange;
    text-shadow: 1px 1px purple;
  }
  to {
    color: white;
    text-shadow: 1px 1px black;
  }
  0% {
    transform: rotate(0deg);
  }
  80% {
    transform: rotate(0deg);
  }
  85% {
    transform: rotate(10deg);
  }
  95% {
    transform: rotate(-10deg);
  }
  100% {
    transform: rotate(0deg);
  }
}
span.wiggle1 {
  display: inline-block;
  animation: wiggle 2s infinite;
}
</style>