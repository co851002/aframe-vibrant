<template>
  <!-- Primitives(Shapes). -->
  <a-entity class="objectTest">
    <a-box position="-1 0.6 -3" rotation="0 45 0" color="#4CC3D9"></a-box>
    <a-sphere position="0 1.35 -5" radius="1.25" color="#EF2D5E"></a-sphere>
    <a-cylinder position="1 0.85 -3" radius="0.5" height="1.5" color="#FFC65D"></a-cylinder>
    <a-plane position="0 .1 -4" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane>
  </a-entity>

</template>

<script>
export default {
  name: 'objectTest',
  data () {
    return {}
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
