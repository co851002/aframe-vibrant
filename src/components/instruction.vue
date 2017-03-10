<template>
<!-- 360-instruction label -->
<a-curvedimage class="instruction" src="#instruction" height="1" position="0 1.2 -2" rotation="0 -210 0" radius="0.7" theta-length="72" scale="0.5 0.5 0.5">
  <a-animation attribute="rotation" easing="ease-in-out-cubic" repeat="3" from="0 -200 0" to="0 -230 0" delay="200" direction="alternate" dur="900"></a-animation>
</a-curvedimage>
</template>

<script>
export default {
  name: 'instruction',
  data () {
    return {}
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
