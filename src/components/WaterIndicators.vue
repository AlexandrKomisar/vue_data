<template>
    <div class="water">
        <h3>water</h3>
        <p>{{$store.state.water}}</p>
    </div>
</template>

<script>
export default {
  name: 'WaterIndicators',
  // data(){
  //   return{
  //   }
  // },
  props: {
    msg: String
  }
}
</script>

<style lang="scss" scoped>
.water{
  background-color: #2d58f4f4;
  color: #ffffff;
}
</style>
