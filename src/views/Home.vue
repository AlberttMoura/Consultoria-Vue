<template>
  <div class="home">
    <img class="port-img" src="@/assets/images/home/grapetree.jpg" alt="">
    <div class="content">
      <p class="title">Plantdex ajuda você a gerenciar e potencializar os resultados do seu negócio.</p>
      <p class="text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla rutrum enim nec mattis lobortis. Donec at tortor vitae tellus commodo venenatis. Phasellus euismod tortor leo, et aliquam libero lobortis posuere. Praesent a semper orci. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam erat volutpat. Integer vel ex ac dui feugiat hendrerit. Morbi est erat, pellentesque id laoreet sed, bibendum vitae enim. Aenean ornare venenatis odio vel consectetur. Aenean mollis magna vitae est interdum, non tincidunt odio pellentesque. Donec viverra arcu vitae leo vestibulum, sed malesuada eros faucibus.</p>
      <p class=title>Parceiros</p>
      <div class="partnes">
        <img class="comp-logo" src="@/assets/images/home/ursallogo.png" alt="">
        <img class="comp-logo" src="@/assets/images/home/umbrellalogo.png" alt="">
        <img class="comp-logo" src="@/assets/images/home/acmelogo.png" alt="">
        <img class="comp-logo" src="@/assets/images/home/oxemudaslogo.jpg" alt="">
      </div>
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

<style scoped>

.home {
  width: 100%;
  height: 100%;
  overflow: hidden;
}

.port-img {
  height: 500px;
  border-bottom: 0px solid #313131;
}

.content {
  padding-left: 8%;
  padding-right: 8%;
}

.content .title{
  font-size: 24px;
  margin-bottom: 40px;
  margin-top: 40px;
  font-weight: 600;
}

.partnes .comp-logo {
  width: 250px;
  height: auto;
  padding-bottom: 50px;
}

.partnes {
  text-align: center;
}
@media screen and (min-width: 740px) {
  .port-img {
    width: 100vw;
    height: 600px;
  }

  .partnes {
    display: flex;
  }

  .partnes .comp-logo {
    overflow: hidden;
    margin-right: 60px;
  }
}
</style>
