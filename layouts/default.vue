<template>
  <div class="root">
    <nuxt />
  </div>
</template>
<style lang="stylus">
@import '../node_modules/normalize-stylus/normalize.styl'
@import url('https://fonts.googleapis.com/css?family=Poppins&display=swap');
@font-face {
    font-family: Museo;
    src: url("../assets/museo.otf") format("opentype");
}
main = #2708a2
.root
  background main
  min-height 100vh
  font-family: 'Poppins', sans-serif;
a
  text-decoration none
  color white
</style>
