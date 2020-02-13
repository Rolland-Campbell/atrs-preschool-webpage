<template>
  <div class="gymnastics container-fluid">
    <div class="row">
      <div class="titleText">
        <p>
          G
          <span class="moveY">y</span>mnastics
        </p>
      </div>
      <div class="col-12"></div>
    </div>
  </div>
</template>


<script>
export default {
  name: "gymnastics",
  data() {
    return {};
  },
  computed: {},
  methods: {},
  components: {}
};
</script>


<style scoped>
.gymnastics {
  background-color: darkkhaki;
  min-height: 90vh;
}

.titleText {
  color: white;
  text-shadow: 1px 1px black;
  font-size: 10vh;
  position: relative;
  top: 10vh;
  left: 3vw;
  /* transform: rotate(-40deg); */
}

span.moveY {
  display: inline-block;
  animation: wiggleDropRoll 1s infinite;
}

@keyframes wiggleDropRoll {
  0% {
    transform: rotate(0deg);
  }
  10% {
    transform: rotate(10deg);
  }
  15% {
    transform: rotate(-10deg);
  }
  20% {
    transform: translateY(-5vh);
  }
}
</style>