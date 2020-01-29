<template>
  <div id="app" >
    
    <navbar/>
    <home/>
    <card/>
    <footerweb/>

  </div>
</template>

<script>
import navbar from './components/navbar.vue';
import home from './components/home.vue';
import card from './components/card.vue';
import footerweb from './components/footerweb.vue';

export default {
  
  name: 'app',
  components: {
    navbar,
    home,
    card,
    footerweb
  }
}
</script>

<style>

</style>
