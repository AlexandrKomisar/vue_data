<template>
  <div class="home">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <SubscriptionFee/>
    <WaterIndicators/>
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue'
import SubscriptionFee from '@/components/SubscriptionFee.vue'
import WaterIndicators from '@/components/WaterIndicators.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    SubscriptionFee,
    WaterIndicators
  }
}
</script>
