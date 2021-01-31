<template>
  <footer class="footer">
      <p>Rua Fulano da Silva PE</p>
      <p>+55 81 1234-5678</p>
  </footer>
</template>

<script>
export default {

}
</script>

<style scoped>

.footer {
    background-color: #313131;
    position: relative;
    width: 100%;
    height: 100%;
    bottom: 0;
    height: 40px;
    margin-top: auto;
    clear: both;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding-right: 3%;
    padding-left: 3%;
}

.footer, p {
    color: #fff;
    font-size: 15px;
}

</style>
