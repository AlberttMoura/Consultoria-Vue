<template>
  <div class="home">
    <img class="port-img" src="@/assets/images/grapetree.jpg" alt="">
    <div class="content">
      Hello
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  components: {
  }
}
</script>

<style>
.home {
  grid-area: p;
  width: 100%;
  height: 100%;
}

.port-img {
  width: 100%;
  border-bottom: 0px solid #313131;
  
}
</style>
