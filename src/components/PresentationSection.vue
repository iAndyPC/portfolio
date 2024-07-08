<script setup>

</script>

<template>
  <section class="presentation-section">
    <div class="wrap-for-photo">
      <img class="photo" src="../assets/photo-no-back-black.png" alt="my photo">
    </div>
    <h1>Building digital
      products, brands, and
      experience.</h1>
  </section>
</template>

<style scoped>
.presentation-section {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  height: 430px;
  background-color: var(--background-color-gray);
  border-bottom-left-radius: var(--border-radius-section);
  border-bottom-right-radius: var(--border-radius-section);
  border-left: 1px solid var(--border-color);
  border-right: 1px solid var(--border-color);
  border-bottom: 1px solid var(--border-color);
}

.wrap-for-photo {
  position: relative;
  background: linear-gradient(rgb(255, 255, 254) 0%, rgba(255, 255, 254, 0) 100%);
  width: 128px;
  height: 128px;
  border-radius: 50%;
}
.photo {
  position: absolute;
  left: 4px;
  top: 4px;
  width: 120px;
  height: 120px;
  border-radius: 50%;
}
h1 {
  width: 77.4%;
}
</style>