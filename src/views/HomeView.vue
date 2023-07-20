<template>
  <Banner />
  <h1>Monte seu hamburguer</h1>
  <main id="main-homeview" class="main-container">
    <div id="form-div">
      <BurgerForm />
    </div>
    <MainImage />
   
  </main>
</template>

<script>
  import Banner from '../components/Banner.vue'
  import BurgerForm from '../components/BurgerForm.vue'
  import MainImage from '../components/MainImage.vue'

  export default {
    name: 'Home',
    components: {
      Banner,
      BurgerForm,
      MainImage
    }
  }
</script>

<style scoped>
  #main-homeview{
    display: flex;
  }

  #form-div{
    width: 50vw;
  }
</style>

