<script setup>

</script>

<template>
  <section class="presentation-section">
    <div class="wrap-for-photo">
      <img class="photo" src="../assets/photo.jpg" alt="my photo">
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
  border-bottom-left-radius: 80px;
  border-bottom-right-radius: 80px;
  border-left: 1px solid var(--border-color);
  border-right: 1px solid var(--border-color);
  border-bottom: 1px solid var(--border-color);
}

.wrap-for-photo {

}
.photo {
  width: 128px;
  height: 128px;
}
</style>