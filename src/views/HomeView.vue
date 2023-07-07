<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <WaterIndicators/>
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue'
import WaterIndicators from '@/components/WaterIndicators.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    WaterIndicators
  }
}
</script>
