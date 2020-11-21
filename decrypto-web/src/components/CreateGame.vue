<template>
  <div>
    <blockquote>
      Decrypto is a game where two teams try to figure out the other teams code.
    </blockquote>
    <div id="createGame">
      <button v-on:click="createGame">Create game!</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "CreateGame",
  methods: {
    createGame: function () {
      alert("creating game");
    },
  },
};
</script>

<style scoped>
</style>