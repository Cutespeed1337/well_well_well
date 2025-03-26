<script>
export default {
  props: {
    title: String,
    cards: Array,
  },
  methods: {},
  mounted() {
    console.log(this.cards);
  },
};
</script>
<template>
  <h1>{{ title }}</h1>
  <div class="cards" v-if="cards">
    <MixCard
      v-for="card in cards"
      :key="card.id"
      :name="card.name"
      :img="card.img"
    ></MixCard>
  </div>
</template>
<style scoped>
.cards {
  display: flex;
  align-items: center;
  gap: 20px;
}

h1 {
  color: #fff;
}
</style>
