<template>
<!-- Beer can component -->
<a-entity class="logo">
  <a-curvedimage src="#logo" radius="1.7" height="1" width="150" position="-0.65 3.2 -1.5" rotation="10 -240 0"  theta-length="74"
  scale="1 1 1">
    <!--a-animation attribute="rotation" easing="ease-in-out-cubic" repeat="3" from="0 -200 0" to="0 -230 0" delay="200" direction="alternate" dur="900"></a-animation-->
  </a-curvedimage>

</a-entity>


</template>

<script>
export default {
  name: 'logo',
  data () {
    return {}
  }

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
