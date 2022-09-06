<template>
  <div id="app">
    <hotel-component/>
  </div>
</template>

<script>
import HotelComponent from './components/HotelComponent.vue';

export default {
  name: 'App',
  components: {
    HotelComponent,
   
},
setup() {
    return {};
  },

}
</script>

<style>
#app{
  margin: 0 auto;
  max-width: 1250px;
  font-family: 'Montserrat', sans-serif;

}
</style>
