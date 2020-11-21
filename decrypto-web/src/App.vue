<template>
  <div id="app">
    <h1>Decrypto</h1>
    <CreateGame />
    <SelectTeam />
    <PlayScreen />
  </div>
</template>

<script>
import CreateGame from "./components/CreateGame.vue";
import SelectTeam from "./components/SelectTeam.vue";
import PlayScreen from "./components/PlayScreen.vue";

export default {
  name: "App",
  components: {
    CreateGame,
    SelectTeam,
    PlayScreen,
  },
};
</script>

<style>
body {
  background-color: rgba(220, 220, 220, 0.3);
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
button {
  color: whitesmoke;
  font-weight: bold;
  background-color: #4682b4;
  border: 1px solid black;
  border-radius: 8px;
  padding: 10px 30px 10px 30px;
  margin-top: 20px;
}
</style>
