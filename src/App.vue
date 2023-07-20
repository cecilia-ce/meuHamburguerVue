<template>
  <Menu :logo="logo_src" :alt="app_name" />
  <RouterView />
  <Rodape />
</template>

<script>
import { RouterLink, RouterView } from 'vue-router'
import Menu from './components/Menu.vue'
import Rodape from './components/Rodape.vue'

export default {
  components: {
    Menu,
    Rodape
  },
  data(){
    return{
      logo_src: "/img/logo.png",
      app_name: "Meu lanchinho"
    }
  }
}
</script>

<style>
  *{
    font-family: helvetica;
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }

  .main-container{
    margin: 50px;
    min-height: 250px;
  }

  h1 {
    text-align: center;
    font-size: 42px;
    margin-bottom: 30px;
    color: #222
  }
</style>
