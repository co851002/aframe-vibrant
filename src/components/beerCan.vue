<template>
<!-- Beer can component -->




<a-entity class="beerCan"  >
  <a-curvedimage src="#beerCan" height="7" position="-2 -2.5 -12" rotation="-40 -200 0" radius="5.7" theta-length="50" scale="1 1 1 " transparent="true">
  </a-curvedimage>

  <a-curvedimage src="#beerCan" height="7" position="1 5 -12" rotation="40 -200 0" radius="5.7" theta-length="50" scale="1 1 1 " transparent="true">
  </a-curvedimage>

  <a-curvedimage src="#beerCan" height="7" position="-2 2 -8" rotation="0 -220 0" radius="5.7" theta-length="60" scale="1 1 1" transparent="true">
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
