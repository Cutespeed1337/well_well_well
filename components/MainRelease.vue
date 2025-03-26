<script>
export default {
  data() {
    return {};
  },
  methods: {},
  props: {
    name: String,
    desc: String,
    img: String,
  },
};
</script>
<template>
  <div class="wrapper">
    <img class="back" :src="img" alt="" />
    <h1>{{ name }}</h1>
    <h3>{{ desc }}</h3>
    <button class="btn">Play</button>
  </div>
</template>
<style scoped>
.wrapper {
  position: relative;
  height: 70vh;
  display: flex;
  flex-direction: column;
  gap: 10px;
  justify-content: flex-end;
  overflow: hidden;
  padding: 40px 10px;
}

h1,
h3 {
  padding: 10px;
  border-radius: 20px;
  width: fit-content;
  background-color: #ffdb4d;
  font-weight: 700;
  z-index: 2;
}

.btn {
  width: fit-content;
  background-color: blue;
  padding: 10px 20px;
  color: #ffdb4d;
  border-radius: 20px;
  font-size: large;
  z-index: 2;
  cursor: pointer;
}

.back {
  position: absolute;
  top: 0;
  left: 0;
}
</style>
