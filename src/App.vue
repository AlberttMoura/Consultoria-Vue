<template>
  <div class="app">
    <Navbar/>
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
  overflow: auto;
  display: grid;;
  grid-template-columns: 1fr 1fr 1fr 1fr 1fr;
  grid-template-rows: 80px auto 40px;
  grid-template-areas: 'h h h h h'
                       'p p p p p'
                       'f f f f f';
}
</style>
