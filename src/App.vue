<template>
  <div id="app row">
    <div class="col text-right" id="nav">
      <router-link to="/">Home &nbsp;</router-link>|
      <router-link to="/dance">Dance &nbsp;</router-link>|
      <router-link to="/theatre">Theatre &nbsp;</router-link>|
      <router-link to="/gymnastics">Gymnastics &nbsp;</router-link>|
      <router-link to="/music">Music &nbsp;</router-link>|
      <router-link to="/staff">Our Staff&nbsp;</router-link>|
      <router-link to="/about">About&nbsp;</router-link>
    </div>
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: grey;
}

#nav a.router-link-exact-active {
  color: hotpink;
}

.logoSize {
  height: 10vh;
  width: 10vw;
}
</style>
