
<template lang="html">
  <div id="scene">
    <a-scene >
      <a-assets>
        <img id="groundTexture" src="https://cdn.aframe.io/a-painter/images/floor.jpg">
        <img id="skyTexture" src="https://ucarecdn.com/7661dda0-8883-43c1-87c6-2dcab52f1964/">
        <img id="coors_logo" src="https://ucarecdn.com/c7149ba5-b102-4b6b-891d-c7e941347014/">
        <img id="instruction" src="https://ucarecdn.com/d6af88be-b8aa-43ef-9041-0a8dafe17f72/">
        <img id="mountains" src="https://ucarecdn.com/8d6e57d1-c8a9-4e3c-89d2-742a447ff3bf/">
        <img id="beerCan" src="https://ucarecdn.com/b8afc3b4-05a9-49eb-afee-0e33a4eb3686/">
        <img id="logo" src="https://ucarecdn.com/de16c46d-9c4a-41c1-bbbb-961433fe2637/">
        <img id="stubhub" src="https://ucarecdn.com/28bcff7c-2ac6-4008-bf4a-0ba026a2be95/">
        <img id="clouds" src="https://ucarecdn.com/ef320bb4-f2d7-41f2-912d-1614a6039fdc/">
      </a-assets>
      <instruction></instruction>
      <ground></ground>
      <mountains></mountains>
      <beerCan></beerCan>
      <logo></logo>
      <stubhub></stubhub>
      <clouds></clouds>

      <!--a-sky color="#AAB" scale="" material="shader:flat;color:#AAB" geometry="mergeTo:null;primitive:sphere;radius:5000;segmentsHeight:20;segmentsWidth:64"></a-sky-->

      <a-entity id="camera" camera="userHeight: 1.6" cameraposition="0 0 0" look-controls rotation="0 0 0">
      </a-entity>


    </a-scene>
  </div>
</template>

<script>
import objectTest from './components/objectTest'
import instruction from './components/instruction'
import ground from './components/ground'
import mountains from './components/mountains'
import beerCan from './components/beerCan'
import logo from './components/logo'
import stubhub from './components/stubhub'
import clouds from './components/clouds'

import 'aframe'
import 'aframe-mountain-component'
import 'aframe-sun-sky'
import 'aframe-particle-system-component'
import 'aframe-extras'
import 'aframe-event-set-component'
import 'aframe-orbit-controls-component'

export default {
  name: 'app',
  components: {
    objectTest,
    instruction,
    ground,
    mountains,
    beerCan,
    logo,
    stubhub,
    clouds
  }
}
</script>

<style lang="css" scoped>
#scene {
    display: block;
    position: absolute;
    height: 100%;
    width: 100%;
}
</style>
