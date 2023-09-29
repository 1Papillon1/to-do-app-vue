<!-- Making list image: <a href="http://www.freepik.com">Designed by rawpixel.com / Freepik</a> -->
<template>
  <div class="layout">
    <div class="flex">

      <div class="flex__box">
        <h1 class="flex__box__title">Welcome to To Do App</h1>
        <h2 class="flex__box__title flex__box__title--secondary">Simple To Do App developed using Vue.js</h2>
        <button class="button">ENTER SITE</button>
      </div>

      <div class="flex__box">
        <img  class="image" src="../assets/Vectors/making_list.jpg" />
      </div>

    </div>
  </div>
</template>

<script>
export default {
  name: 'MainPage',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>



</style>
