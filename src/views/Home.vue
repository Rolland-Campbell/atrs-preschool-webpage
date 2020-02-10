<template>
  <div class="home container-fluid">
    <div class="row">
      <CarouselHome />
    </div>
    <div class="row">
      <div
        class="homeText col-md-8 offset-md-2"
      >Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla perferendis illum nesciunt porro dolor ipsum reiciendis alias, temporibus aliquid beatae veritatis unde eius sed? Quae maiores dolores dolorum iusto quibusdam. Lorem ipsum dolor sit, amet consectetur adipisicing elit. Qui fugit quia similique corrupti amet temporibus reprehenderit maiores itaque quisquam consequuntur numquam quis, corporis ut aliquid repellendus quam ratione iusto soluta! Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam repudiandae aliquam totam expedita voluptatibus eveniet necessitatibus rem commodi! Molestiae, aperiam et rem illo ab corrupti! Soluta nam iure ullam suscipit.</div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import CarouselHome from "../components/carousel-home";
export default {
  name: "home",
  components: { CarouselHome }
};
</script>

<style scoped>
.home {
  height: 90vh;
  background-color: hotpink;
}

.homeText {
  color: white;
  padding-top: 2vh;
}
</style>
