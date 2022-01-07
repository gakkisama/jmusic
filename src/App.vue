<template>
  <div id="app">
    <div class="test"></div>
    <router-view></router-view>
  </div>
</template>

<style lang="scss">
// #app {
//   font-family: Avenir, Helvetica, Arial, sans-serif;
//   -webkit-font-smoothing: antialiased;
//   -moz-osx-font-smoothing: grayscale;
//   text-align: center;
//   color: #2c3e50;
// }

.test {
  width: 100px;
  height: 100px;
  background-color: #f00;
  transform: translate(100px,100px);
}
</style>
