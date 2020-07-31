<template>
  <div id="app">
    <wilbert-top-header></wilbert-top-header>
    <wilbert-header></wilbert-header>
    <wilbert-slider></wilbert-slider>
    <div>
      <wilbert-home msg="Serving Our Customers One Quality Product at a Time."/>
    </div>
  </div>
</template>


<script>
import TopHeader from './components/TopHeader.vue'
import Header from './components/Header.vue'
import Slider from './components/Slider.vue'
import Home from './components/Home.vue'


export default {
  name: 'App',
  components: {
    'wilbert-top-header' : TopHeader,
    'wilbert-header' : Header,
    'wilbert-slider' : Slider,
    'wilbert-home' : Home
  }
}
</script>


<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
