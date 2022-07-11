<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <img id="logo" alt="Wails logo" src="./assets/images/logo-universal.png"/>
  <HelloWorld/>


    <audio id="my-audio">
      <source src="./assets/audio/final.mp3" type="audio/mpeg"/>
    </audio>

    <br/>
    <br/>

    <button style="padding: 3px; border-radius: 4px; font-size:2em" id="play-audio" onclick="document.getElementById('my-audio').play();">
      <img src="./assets/images/voice.svg" alt="button"  height="25"/>
      Test sound
    </button>

</template>

<style>
#logo {
  display: block;
  width: 50%;
  height: 50%;
  margin: auto;
  padding: 10% 0 0;
  background-position: center;
  background-repeat: no-repeat;
  background-size: 100% 100%;
  background-origin: content-box;
}
</style>
