<template>
    <div class="services">
        <img class="port-img" src="@/assets/images/services/tractor.jpg" alt="">
        <div class="content">
            <p class="title">Serviços</p>
            <div class="services-area">
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.services {
    height: 100%;
    width: 100%;
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
