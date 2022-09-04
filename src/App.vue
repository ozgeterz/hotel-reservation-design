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
  max-width: 1250px;
  
}
</style>
