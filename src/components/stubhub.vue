<template>
<!-- Beer can component -->
<a-entity class="stubhub">
  <a-curvedimage src="#stubhub" radius="5.7" height="1" width="600"
  position="2.5 4.5 -5" rotation="0 320 0"  theta-length="40"
  scale="2 2 2">
    <!--a-animation attribute="rotation" easing="ease-in-out-cubic" repeat="3" from="0 -200 0" to="0 -230 0" delay="200" direction="alternate" dur="900"></a-animation-->
  </a-curvedimage>

</a-entity>


</template>

<script>
export default {
  name: 'stubhub',
  data () {
    return {}
  }

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
