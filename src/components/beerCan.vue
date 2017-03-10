<template>
<!-- Beer can component -->
<a-entity class="beerCan">
  <a-curvedimage src="#beerCan" height="1" position="-0.08 1.6 -2.2" rotation="-40 -200 0" radius="0.6" theta-length="74" scale="0.6 0.6 0.6">
    <!--a-animation attribute="rotation" easing="ease-in-out-cubic" repeat="3" from="0 -200 0" to="0 -230 0" delay="200" direction="alternate" dur="900"></a-animation-->
  </a-curvedimage>

  <a-curvedimage src="#beerCan" height="1" position="0.2 1.99 -2.2" rotation="40 -220 0" radius="0.6" theta-length="70" scale="0.6 0.6 0.6">
    <!--a-animation attribute="rotation" easing="ease-in-out-cubic" repeat="3" from="0 -200 0" to="0 -230 0" delay="200" direction="alternate" dur="900"></a-animation-->
  </a-curvedimage>

  <a-curvedimage src="#beerCan" height="1" position="0.1 1.85 -1.95" rotation="0 -200 0" radius="0.6" theta-length="70" scale="0.6 0.6 0.6">
    <!--a-animation attribute="rotation" easing="ease-in-out-cubic" repeat="3" from="0 -200 0" to="0 -230 0" delay="200" direction="alternate" dur="900"></a-animation-->
  </a-curvedimage>
</a-entity>


</template>

<script>
export default {
  name: 'beerCan',
  data () {
    return {}
  }

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
