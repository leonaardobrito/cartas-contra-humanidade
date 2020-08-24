<template>
  <v-app dark>
    <v-main>
      <v-container class="board">
        <nuxt />
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
export default {
  data() {
    return {
      title: 'Vuetify.js',
    }
  },
}
</script>

<style>
* {
  align-items: center;
  overflow: auto;
}
.board {
  display: flex;
  background-color: darkslategrey;
  border-radius: 8px;
  width: clamp(1000px, 92vw, 95vw);
  height: clamp(860px, 97vh, 98vh);
  overflow: hidden;
  padding: 0;
}
</style>
