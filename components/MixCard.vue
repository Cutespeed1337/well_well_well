<script>
export default {
  data() {
    return {};
  },
  methods: {},
  props: {
    name: String,
    img: String,
  },
};
</script>
<template>
  <div class="card">
    <img :src="img" alt="" />
    <span class="name">{{ name }}</span>
  </div>
</template>
<style scoped>
.card {
  display: flex;
  flex-direction: column;
  gap: 20px;
}

img {
  width: 200px;
  height: 100px;
  object-fit: cover;
  border-radius: 20px;
}

.name {
  color: #fff;
  font-size: large;
}
</style>
