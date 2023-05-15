<template>
  <div id="app">
    <h1 style="margin-bottom: 40px;">Vue 2 Slider using vue-slider-component</h1>
    <vue-slider v-model="value" />
  </div>
</template>

<script>
import VueSlider from 'vue-slider-component'
import 'vue-slider-component/theme/antd.css'
export default {
  name: 'App',
  components: {
    VueSlider,
  },

  data() {
    return {
      value: 0,
    }
  },
}
</script>

<style>
#app {
  padding: 20px;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.vue-slider{
  height: 25px !important;
}
.vue-slider-dot{
  width: 25px !important;
  height: 25px !important;
}
</style>
