<template>
  <div>
    <WhiteCard class="wcard" />
    <WhiteCard />
    <WhiteCard />
    <WhiteCard />
    <WhiteCard />
    <WhiteCard />
    <WhiteCard />
    <EnemyInfo />
  </div>
</template>

<script>
import WhiteCard from '@/components/WhiteCard.vue'
import EnemyInfo from '@/components/EnemyInfo.vue';
export default {
  components: {
    WhiteCard,
    EnemyInfo
  },
}
</script>

<style scoped>
* {
  font-size: x-small;
  margin: 2px;
}
</style>
