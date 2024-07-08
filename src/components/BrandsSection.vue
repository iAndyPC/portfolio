<script setup>

</script>

<template>
  <section class="section-brands">
    <div class="running_img">
      <div class="row">
        <img src="https://fakeimg.pl/160x40/" alt="red wall">
        <img src="https://fakeimg.pl/160x40/" alt="yellow flower">
        <img src="https://fakeimg.pl/160x40/" alt="green forest">
        <img src="https://fakeimg.pl/160x40/" alt="blue rose">

        <img src="https://fakeimg.pl/160x40/" alt="red wall">
        <img src="https://fakeimg.pl/160x40/" alt="yellow flower">
        <img src="https://fakeimg.pl/160x40/" alt="green forest">
        <img src="https://fakeimg.pl/160x40/" alt="blue rose">
      </div>
    </div>
  </section>
</template>

<style scoped>
.section-brands {
  background-color: var(--background-color-white);
  position: relative;
  width: 100%; height: 200px;
  overflow: hidden;
  border-bottom-left-radius: var(--border-radius-section);
  border-bottom-right-radius: var(--border-radius-section);
  border-left: 1px solid var(--border-color);
  border-right: 1px solid var(--border-color);
  border-bottom: 1px solid var(--border-color);
}

.running_img {
  position: absolute;
  left: 50%; top: 43%;
  display: flex; flex-flow: column nowrap;
  width: 100%; height: 40px;
  overflow: hidden;
  transform: translate(-50%, -50%);
}

.row {
  display: flex; flex-flow: row nowrap;
  width: min-content;
}
.row:nth-of-type(1) { animation: slide 20s linear infinite; }

.row > img {
  object-fit: cover;
  margin-right: 60px;
}

@keyframes slide { to { transform: translatex(-50%); } }
</style>