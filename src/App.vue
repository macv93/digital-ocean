<template>
  <div id="app">
    <Hola name="manuel cañarte"/>
    <img alt="manny" src="./assets/manny.png">
    <p>© Manuel Cañarte {{formatTime(Date.now())}}</p>
  </div>
</template>

<script>
import Hola from './components/Hola.vue'

export default {
  name: 'App',
  components: {
    Hola
  },
  methods: {
    formatTime: function (time){
      const currentTime = new Date(time)
      return currentTime.toDateString();
    }
  }

}
</script>

