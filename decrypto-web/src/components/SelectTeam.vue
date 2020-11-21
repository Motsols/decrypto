<template>
  <div class="selectTeam">
    <h2>Select team</h2>
    <div class="team teamBlue">
      <h2>Team Blue</h2>
    </div>
    <div class="team teamRed">
      <h2>Team Red</h2>
    </div>
  </div>
</template>

<script>
export default {
  name: "SelectTeam",
  props: {
    gameId: String,
  },
};
</script>

<style scoped>
.selectTeam {
  margin-top: 40px;
}
.team {
  display: inline-block;
  border: 3px solid blue;
  border-radius: 30px 0px;
  margin-right: 50px;
  margin-top: 50px;

  padding: 40px;
}
.teamBlue {
  border: 3px solid blue;
}
.teamRed {
  border: 3px solid red;
}
</style>