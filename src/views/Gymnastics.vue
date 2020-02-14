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
}
</style>