<template>
  <div id="playingField">
    <div id="teamBlue" class="team">
      <table class="table words">
        <tr class="crypto">
          <th>#1<br />Apple</th>
          <th>#2<br />Summer</th>
          <th>#3<br />Moon</th>
          <th>#4<br />New York</th>
        </tr>
        <tr>
          <td>Fruit</td>
          <td>Swimming</td>
          <td></td>
          <td>Smog</td>
        </tr>
        <tr>
          <td>Orange</td>
          <td></td>
          <td>Dust</td>
          <td>Busy</td>
        </tr>
      </table>
      <div class="clues">
        <h3>New clues</h3>
        <table>
          <tr class="crypto">
            <td>Plum</td>
            <td>
              <select Name="Clue1">
                <option value="1">#1</option>
                <option value="2">#2</option>
                <option value="3">#3</option>
                <option value="4">#4</option>
              </select>
            </td>
          </tr>
          <tr>
            <td>Cold</td>
            <td>
              <select Name="Clue2">
                <option value="1">#1</option>
                <option value="2">#2</option>
                <option value="3">#3</option>
                <option value="4">#4</option>
              </select>
            </td>
          </tr>
          <tr>
            <td>Blocks</td>
            <td>
              <select Name="Clue3">
                <option value="1">#1</option>
                <option value="2">#2</option>
                <option value="3">#3</option>
                <option value="4">#4</option>
              </select>
            </td>
          </tr>
        </table>
        <button>Save guess</button>
        <br />
        <div>Todo: Generate a code</div>
        <div>Todo: Enter clues for code</div>
      </div>
    </div>
    <div id="teamRed" class="team">
      <table class="table words">
        <tr class="crypto">
          <th>#1<br />????</th>
          <th>#2<br />????</th>
          <th>#3<br />????</th>
          <th>#4<br />????</th>
        </tr>
        <tr>
          <td>1</td>
          <td>2</td>
          <td>3</td>
          <td>4</td>
        </tr>
        <tr>
          <td>1</td>
          <td>2</td>
          <td>3</td>
          <td>4</td>
        </tr>
      </table>
      <div class="clues">
        <h3>New clues</h3>
        <table>
          <tr class="crypto">
            <td>Grass</td>
            <td>
              <select Name="Clue1">
                <option value="1">#1</option>
                <option value="2">#2</option>
                <option value="3">#3</option>
                <option value="4">#4</option>
              </select>
            </td>
          </tr>
          <tr>
            <td>Egg</td>
            <td>
              <select Name="Clue2">
                <option value="1">#1</option>
                <option value="2">#2</option>
                <option value="3">#3</option>
                <option value="4">#4</option>
              </select>
            </td>
          </tr>
          <tr>
            <td>Moose</td>
            <td>
              <select Name="Clue3">
                <option value="1">#1</option>
                <option value="2">#2</option>
                <option value="3">#3</option>
                <option value="4">#4</option>
              </select>
            </td>
          </tr>
        </table>
        <button>Save guess</button>
        <br />
        <div>Todo: Generate a code</div>
        <div>Todo: Enter clues for code</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "PlayScreen",
};
</script>

<style scoped>
#playingField {
  display: flex;
  justify-content: space-around;
}
.team {
  display: inline-block;
  min-width: 700px;
  margin-top: 30px;
}
#teamBlue {
  background-color: rgb(171, 199, 255);
  margin-left: auto;
  margin-right: auto;
}
#teamRed {
  background-color: rgb(255, 143, 152);
  margin-left: auto;
  margin-right: auto;
}
.table {
  margin-left: auto;
  margin-right: auto;
  width: 100%;
}
.words {
  margin-left: auto;
  margin-right: auto;
}
.crypto th {
  font-size: 20px;
  padding-bottom: 10px;
}
.table tr td {
  border-top: 1px solid gray;
}
.clues {
  margin: 60px 0px 40px 30px;
  text-align: left;
}
</style>