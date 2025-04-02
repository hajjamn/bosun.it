<script>
export default {
  components: {},
  data() {
    return {};
  },
};
</script>

<template>
  <header>
    <section class="position-relative">
      <img
        src="../assets/header_logo.png"
        alt="bosun logo"
        class="header-logo position-absolute"
      />
      <div class="header-container container py-3">
        <h1 class="header-title">Bosun's Store</h1>
        <h2 class="header-subtitle">Forniture Nautiche</h2>
      </div>
    </section>
  </header>
</template>

<style scoped>
/* .bg-header {
  background-color: var(--brand-color-default);
} */

.header-container {
  position: relative;
  margin-left: 200px;
}

.header-title {
  color: var(--accent-color-default);
}

.header-subtitle {
  color: var(--accent-color-default);
  font-size: medium;
}

.header-logo {
  height: 50vh;
}
</style>
