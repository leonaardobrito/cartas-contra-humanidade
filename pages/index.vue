<template>
  <v-row>
    <v-row class="col-12" no-gutters>
      <v-col class="left-enemies" cols="1">
        <EnemySpot id="enemy-1" />
        <EnemySpot id="enemy-2" />
      </v-col>

      <v-spacer />
      <v-col class="playing" justify-content="center" align="center" cols="4">
        <v-row>
          <v-col class="black-cards">

          oie
          </v-col>
        </v-row>

        <v-row>
          <v-col class="pool">

          oieee
          </v-col>
        </v-row>
      </v-col>
      <v-spacer />

      <v-col class="right-enemies" cols="1">
        <EnemySpot id="enemy-3" />
        <EnemySpot id="enemy-4" />
      </v-col>
    </v-row>

    <v-row class="player-container">
      <v-col>
        <PlayerSpot class="player-spot" />
      </v-col>
    </v-row>
  </v-row>
</template>

<script>
import EnemySpot from '@/components/EnemySpot.vue'
import WhiteCard from '@/components/WhiteCard.vue'
import PlayerCard from '@/components/PlayerCard.vue'
import PlayerSpot from '@/components/PlayerSpot.vue'
export default {
  components: {
    EnemySpot,
    WhiteCard,
    PlayerCard,
    PlayerSpot,
  },
}
</script>
<style scoped>
* {
  
  overflow: hidden;
}
#enemy-1 {
  background-color: inherit;
}
#enemy-2 {
  background-color: inherit;
}
#enemy-1 {
  background-color: inherit;
}
#enemy-2 {
  background-color: inherit;
}

.playing {
  background-color: orchid;
  padding: 5px;
}

.black-cards {
  background-color: slategrey;
}
.pool {
  background-color: orangered;
}
.left-enemies {
  display: flex;
  background-color: inherit;
  flex-direction: column;
  justify-content: space-between;
  text-align: left;
  height: clamp(650px, 75vh, 85vmin);
}

.right-enemies {
  display: flex;
  background-color: inherit;
  flex-direction: column;
  justify-content: space-between;
  height: clamp(700px, 75vh, 85vmin);
}
/* .player-spot {
  display: flex;
  justify-self: stretch;
  align-self: stretch;
  align-content: center;
  align-items: center;
  width: clamp(800px, 99.5%, 100%);
} */
</style>
