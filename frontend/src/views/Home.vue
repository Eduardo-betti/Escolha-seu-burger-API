<template>
  <Banner />
  <div class="main-conteiner">
    <h1>Monte seu Hamburger:</h1>
    <BurgerForm />
  </div>
</template>

<script>
import Banner from '../components/Banner.vue';
import BurgerForm from '../components/BurgerForm.vue';

export default {
  name: 'Home',
  components: {
    Banner,
    BurgerForm,
  },
};
</script>
