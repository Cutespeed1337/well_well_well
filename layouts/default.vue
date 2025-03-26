<template>
  <AppHeader></AppHeader>

  <main>
    <slot> </slot>
  </main>
</template>
<style>
main {
  width: 80%;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  gap: 20px;
}
</style>
