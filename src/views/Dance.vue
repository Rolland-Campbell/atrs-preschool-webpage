<template>
  <div class="dance container-fluid">
    <div class="row headerDance">
      <div class="col-12 d-none col-md-3">
        <img src="../assets/dancepicleft.jpg" alt class="danceImg1" />
      </div>
      <div class="col-12 col-md-5">
        <h1 class="titleText">
          <span class="char1 hopleft">L</span>
          <span class="char2">E</span>
          <span class="char3">T</span>
          <span class="char4">'</span>
          <span class="char5">S</span>
          <span class="char6 hopup pl-4">D</span>
          <span class="char7">A</span>
          <span class="char8">N</span>
          <span class="char9">C</span>
          <span class="char10">E</span>
          <span class="wiggle1">!!</span>
        </h1>
      </div>
      <div class="col-12 d-none col-md-3">
        <img src="../assets/dancepicright.jpg" alt class="danceImg2" />
      </div>
    </div>
    <div class="row textRow">
      <div class="col-md-6 offset-md-3 danceText">
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Modi tempora quibusdam corporis veniam sint, vel blanditiis voluptas dolores eius voluptatem reprehenderit dolor architecto tenetur corrupti temporibus totam exercitationem nam et! Lorem ipsum dolor sit amet consectetur, adipisicing elit. Explicabo recusandae eos, fugit voluptatem dignissimos iusto in similique veniam perferendis nobis nihil inventore optio autem numquam. Repellendus placeat eveniet ipsa a.</p>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Facere illum recusandae, enim sint voluptatum quam vel beatae quaerat consequatur culpa quia dolore. Beatae sequi sunt fuga obcaecati nostrum delectus laboriosam? Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sequi necessitatibus quas nemo, nobis, itaque quae laboriosam nihil facilis culpa inventore a aperiam maiores eum illo, quibusdam repellat natus libero. Ipsam.</p>
      </div>
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

.danceText {
  padding: 25px;
  color: white;
  font-weight: bold;
  text-shadow: 1px 1px black;
  background-color: rgba(255, 255, 255, 0.253);
  border-radius: 20px;
}

.textRow {
  height: 60vh;
}

span {
  font-size: 8vh;
  font-weight: bold;
}

@media only screen and (max-width: 600px) {
  span {
    font-size: 5vh;
    font-weight: bold;
  }
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
  text-shadow: 1px 1px black;
  padding-top: 5vh;
  display: flex;
  justify-self: center;
  align-items: baseline;
  font-family: "Comic Sans MS", cursive, sans-serif;
  font-weight: bold;
  width: cover;
}

@media only screen and (max-width: 600px) {
  .titleText {
  text-shadow: 1px 1px black;
  padding-top: 5vh;
  display: flex;
  justify-content: center;
  align-items: baseline;
  font-family: "Comic Sans MS", cursive, sans-serif;
  font-weight: bold;
  }
}

@keyframes wiggle1 {
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
  animation: wiggle1 2s infinite;
}

@keyframes hopup {
  0% {
    transform: translateY(-1vh);
  }
}

span.hopup {
  display: inline-block;
  animation: hopup 3s infinite;
}

@keyframes hopleft {
  0% {
    transform: translateX(-1vw);
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

span.hopleft {
  display: inline-block;
  animation: hopleft 4s infinite;
}
</style>