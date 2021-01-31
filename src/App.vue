<template>
  <div class="app">
    <div class="top">
      <Navbar/>
    </div>
    <router-view/>
    <Footer/>
  </div>
</template>

<script>
import Navbar from './components/general/Navbar'
import Footer from './components/general/Footer'

export default {
  components: {
    Navbar,
    Footer
  }
}
</script>

<style>
@font-face {
        font-family: "OpenSans";
        src: url("../src/assets/fonts/Open_Sans/OpenSans-Regular.ttf");
      }

* {
        padding: 0;
        margin: 0;
        box-sizing: border-box;
        color: #474747;
        font-family: 'OpenSans';
      }

.app {
  background-color: #fff;
  height: auto;
  width: 100%;
}
</style>
