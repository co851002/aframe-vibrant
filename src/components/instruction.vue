<template>
<!-- 360-instruction label -->
<a-curvedimage class="instruction" src="#instruction" height="3.5" width="20" position="0 -5.2 -5.8" rotation="0 -210 0" radius="7.7" theta-length="35" scale="1 1 1">
  <a-animation attribute="rotation" easing="ease-in-out-cubic" repeat="3" from="0 -190 0" to="0 -210 0" delay="200" direction="alternate" dur="900"></a-animation>
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
