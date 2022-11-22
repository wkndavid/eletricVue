<script setup>
import HeaderProfile from './components/HeaderProfile.vue'
import SectionPortifolio from './components/SectionPortifolio.vue'
import SectionProfile from './components/SectionProfile.vue'
</script>

<template>
  <header>
      <HeaderProfile />
  </header>

  <main>
    <SectionPortifolio />
  </main>

  <section>
    <SectionProfile />
  </section>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  margin: 0 auto 2rem;
}
</style>
