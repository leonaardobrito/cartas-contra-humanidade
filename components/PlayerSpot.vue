<template>
  <v-row>
    <v-col class="playerspot" cols="12">
      <PlayerCard class="p-card"/>
      <PlayerCard class="p-card"/>
      <PlayerCard class="p-card"/>
      <PlayerCard class="p-card"/>
      <PlayerCard class="p-card"/>
      <PlayerCard class="p-card"/>
      <PlayerCard class="p-card"/>
    </v-col>
  </v-row>
</template>

<script>
export default {}
</script>
<style scoped>
.playerspot {
  display: flex;
  flex-flow: row wrap;

  align-items: center;
  justify-content: space-evenly;
  background-color: yellow;
  width: inherit;
  overflow: hidden;
  
}
.p-card {
  height: inherit;
  width: 100px;
}
</style>