<template>
  <div id="app">
    <br />
    <HelloWorld id="text" msg="Music" />
    <music />
    <footer class="my-0 pt-0 text-muted text-center text-small">
        
    </footer>
  </div>
</template>
<script>
import HelloWorld from "./components/HelloWorld.vue";
import music from "./components/music.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    music,
  },
};
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #be6398;
  background-size: cover;
  background-image: url();
  
}
#text {
  color: rgb(17, 17, 17);
}
</style>
