<template>
  <header class="navbar">
        <div class="logo">
            <router-link to="/"><img src="@/assets/images/general/planticon.png" alt="" class="logo-image"></router-link>
            <router-link to="/" class="logo-name">Plantdex</router-link>
        </div>
        <div class="menu-links">
            <router-link to="/" class="menu-link">Início</router-link>
            <router-link to="/" class="menu-link">Serviços</router-link>
            <router-link to="/" class="menu-link">Negócios</router-link>
            <router-link to="/about" class="menu-link">Quem Somos</router-link>
        </div>
  </header>
</template>

<script>
export default {

}
</script>

<style scoped>

.navbar {
    background: #fff;
    display: inline-block;
    width: 100%;
    height: 80px;
    align-items: center;
    position:fixed;
    opacity: 0.9;
}

.logo {
    padding-left: 12px;
    display: flex;
    align-items: center;
    border-bottom: #E8E8E8 1px solid;
    height: 48px;
}

.logo-name {
    text-decoration: none;
    font-size: 24px;
    font-weight: 900;
    padding-left: 20px;
}

.logo-image {
    height: 28px;
}

.menu-links {
    display: flex;
    width: 100%;
    justify-content: space-evenly;
    align-items: center;
    height: 32px;
}

.menu-links .menu-link {
    text-decoration: none;
    border: 2px transparent solid;
    transition: color 0.5s, border-bottom 0.5s;
    font-weight: 600;
    font-size: 14px;
}

.menu-links .menu-link:hover {
    color: #56C252;
    border-bottom: 2px #56C252 solid;
}

@media screen and (min-width: 600px) {
    .navbar {
        display: flex;
        height: 70px;
    }

    .logo {
        border: 0;
    }

    .logo .logo-name {
        font-size: 30px;
    }

    .logo-image {
        height: 48px;
    }

    .menu-links .menu-link {
        font-size: 18px;
    }
}
</style>
