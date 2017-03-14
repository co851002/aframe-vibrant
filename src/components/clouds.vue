<template>
<!-- sky (mountains) component -->
<a-sky class="clouds" height="80" radius="5.7" rotation="0 90 0" theta-length="85" transparent="true" src="#clouds">
  <a-animation attribute="rotation" easing="linear"
  repeat="indefinite" from="0 0 0" to="0 360 0" delay="0" direction="normal" dur="20000"></a-animation>
</a-sky>

</template>

<script>
export default {
  name: 'clouds',
  data () {
    return {}
  }

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
