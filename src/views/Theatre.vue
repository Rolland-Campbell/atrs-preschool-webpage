<template>
  <div class="theatre container-fluid">
    <div class="row headerRow">
      <col-3>
        <img src="../assets/masks.png" class="maskPicL" />
      </col-3>
      <div class="col-6 headerText">THEATRE</div>
      <col-3>
        <img src="../assets/masks.png" class="maskPicR" />
      </col-3>
    </div>
    <div class="row textRow">
      <div class="col-md-8 offset-md-2">
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Accusamus eum cum quaerat minus obcaecati mollitia eos nobis labore aliquam odit doloremque vero, tempora, repudiandae dolorem? Officiis error sint voluptatum fuga? Lorem ipsum dolor sit, amet consectetur adipisicing elit. Aut quis, rem laboriosam cumque quibusdam odio officia pariatur, iusto minus harum, facere asperiores molestiae. Expedita delectus cumque, pariatur eaque magni vitae!</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cum, recusandae dolores ab iure consectetur sapiente repellat quia unde quaerat nemo consequuntur dolor molestiae soluta numquam cumque magnam tenetur necessitatibus praesentium? Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga sed, iusto aut ea eius magni minus voluptate maiores ipsam, suscipit ducimus ratione quasi incidunt, excepturi in facere voluptates obcaecati similique.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cum, recusandae dolores ab iure consectetur sapiente repellat quia unde quaerat nemo consequuntur dolor molestiae soluta numquam cumque magnam tenetur necessitatibus praesentium? Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga sed, iusto aut ea eius magni minus voluptate maiores ipsam, suscipit ducimus ratione quasi incidunt, excepturi in facere voluptates obcaecati similique.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cum, recusandae dolores ab iure consectetur sapiente repellat quia unde quaerat nemo consequuntur dolor molestiae soluta numquam cumque magnam tenetur necessitatibus praesentium? Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga sed, iusto aut ea eius magni minus voluptate maiores ipsam, suscipit ducimus ratione quasi incidunt, excepturi in facere voluptates obcaecati similique.</p>
      </div>
    </div>
  </div>
</template>


<script>
export default {
  name: "theatre",
  data() {
    return {};
  },
  computed: {},
  methods: {},
  components: {}
};
</script>


<style scoped>
.theatre {
  background-color: lightgreen;
  min-height: 90vh;
  background-image: url("../assets/scroll.png");
  background-repeat: no-repeat;
  background-position: center;
  background-size: 100% 100%;
}

.headerRow {
  padding-top: 5vh;
  justify-content: center;
  height: 30vh;
}

.headerText {
  color: white;
  font-family: "Times New Roman", Times, serif;
  text-shadow: 1px 1px black;
  font-size: 14vh;
  font-weight: bold;
  display: flex;
  justify-content: center;
}

.maskPicL {
  height: 20vh;
  width: 20vw;
}

.maskPicR {
  -webkit-transform: scaleX(-1);
  transform: scaleX(-1);
  height: 20vh;
  width: 20vw;
}

.textRow {
  height: 40vh;
  font-weight: bold;
  overflow: hidden;
  overflow-y: scroll;
}
</style>