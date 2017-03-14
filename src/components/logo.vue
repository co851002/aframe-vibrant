<template>
<!-- Beer can component -->
<a-entity class="logo">
  <a-curvedimage src="#logo" radius="5.7" height="2" width="300" position="0 4.3 -1" rotation="-8 150 0"  theta-length="64"
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
