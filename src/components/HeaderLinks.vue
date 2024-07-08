<script setup>

</script>

<template>
  <div class="header-links">
    <div class="left">
      <a class="button" href="mailto:iandykarpov@gmail.com">Email</a>
      <a class="button">CV</a>
    </div>
    <div class="right">
      <a class="button button-round"><img class="button-img" src="../assets/linkedin.svg" alt="linkedin"></a>
      <a class="button button-round">CW</a>
    </div>
  </div>
</template>

<style scoped>
.header-links {
  display: flex;
  justify-content: space-between;
  width: 100%;
  padding-top: 40px;
  background-color: var(--background-color-gray);
  border-left: 1px solid var(--border-color);
  border-top: 1px solid var(--border-color);
  border-right: 1px solid var(--border-color);
}
.left {
  display: flex;
  justify-content: space-between;
  width: 180px;
}
.right {
  display: flex;
  justify-content: space-between;
  width: 152px;
}
.button {
  position: relative;
  display: flex;
  width: 85px;
  height: 45px;
  align-items: center;
  justify-content: center;
  background-color: var(--background-color-white);
  border-radius: 60px;
  border: 4px solid var(--border-color-button);
  outline: var(--outline-color-button) solid 1px;
  text-decoration: none;
  color: var(--text-color);
  cursor: pointer;
}
.button-round {
  border-radius: 50%;
  width: 48px;
  height: 48px;
}
.button-img {
  width: 45%;
}
</style>