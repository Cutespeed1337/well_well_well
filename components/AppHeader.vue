<template>
  <header class="wrapper">
    <div class="info">
      <div class="group-logo">
        <img src="../public/favicon.ico" class="logo" alt="" />
        <span class="logo-text">MSHP_MUSIC</span>
      </div>
      <div class="search">
        <label for="search">
          <img src="../public/assets/search.png" alt="" />
        </label>
        <input type="text" placeholder="Поиск" id="search" />
      </div>
    </div>
    <img
      src="https://avatars.mds.yandex.net/get-afishanew/21422/51e1d3cfb2877ca514da6304807b67c7/960x690_noncrop"
      class="profile"
      alt=""
    />
  </header>
</template>
<style scoped>
.wrapper {
  width: 100%;
  padding: 10px 20px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: rgb(0, 0, 49);
  border-bottom: 0.5px solid rgb(55, 55, 84);
  margin-bottom: 20px;
}

.info {
  display: flex;
  align-items: center;
  gap: 20px;
}

.group-logo {
  display: flex;
  align-items: center;
  gap: 7px;
}
.logo-text {
  font-size: large;
  font-weight: 700;
  color: #fff;
}

.profile {
  height: 40px;
  width: 40px;
  object-fit: cover;
  border-radius: 100%;
}

.search {
  background-color: rgb(55, 55, 84);
  display: flex;
  align-items: center;
  gap: 7px;
  border-radius: 10px;
  padding: 5px 10px;
}

.search img {
  height: 20px;
  width: 20px;
  transform: translateY(2px);
}

.search input {
  background: transparent;
  outline: none;
  color: #fff;
}
</style>
