<template>
  <div class="carousel-home offset-md-3 col-md-6">
    <div id="carouselId" class="carousel slide" data-ride="carousel">
      <ol class="carousel-indicators">
        <li data-target="#carouselId" data-slide-to="0" class="active"></li>
        <li data-target="#carouselId" data-slide-to="1"></li>
        <li data-target="#carouselId" data-slide-to="2"></li>
        <li data-target="#carouselId" data-slide-to="3"></li>
      </ol>
      <div class="carousel-inner" role="listbox">
        <div class="carousel-item active">
          <img class="homeCarouselPic" src="../assets/music.jpg" alt="First slide" />
          <div class="carousel-caption d-none d-md-block">
            <h3>Music</h3>
            <p>Introduce your child to the beauty of music.</p>
          </div>
        </div>
        <div class="carousel-item">
          <img class="homeCarouselPic" src="../assets/dance.jpg" alt="Second slide" />
          <div class="carousel-caption d-none d-md-block">
            <h3>Dance</h3>
            <p>Help your child to be active, and expressive.</p>
          </div>
        </div>
        <div class="carousel-item">
          <img class="homeCarouselPic" src="../assets/theatre.jpg" alt="Third slide" />
          <div class="carousel-caption d-none d-md-block">
            <h3>Theatre</h3>
            <p>Build your childs confidence and self-esteem.</p>
          </div>
        </div>
        <div class="carousel-item">
          <img class="homeCarouselPic" src="../assets/gymnastics.jpg" alt="Fourth slide" />
          <div class="carousel-caption d-none d-md-block">
            <h3>Gymnastics</h3>
            <p>Build your childs strength.</p>
          </div>
        </div>
      </div>
      <a class="carousel-control-prev" href="#carouselId" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a class="carousel-control-next" href="#carouselId" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
  </div>
</template>


<script>
export default {
  name: "carousel-home",
  data() {
    return {};
  },
  computed: {},
  methods: {},
  components: {}
};
</script>

<style scoped>
.carousel-home {
  padding-top: 2vh;
}

.carousel-inner {
  border-radius: 20px;
}

.homeCarouselPic {
  height: 50vh;
  width: 100%;
}

p,
h3 {
  text-shadow: 1px 1px black;
}
</style>