<script setup lang="ts">
import Header from './components/Header/Header.vue'
import SectionHero from './components/Sections/SectionHero.vue'
import SectionServices from './components/Sections/SectionServices.vue'
import SectionChoseUs from './components/Sections/SectionChoseUs.vue'
import SectionClients from './components/Sections/SectionClients.vue'
import SectionBudget from './components/Sections/SectionBudget.vue'
import Footer from './components/Layout/Footer.vue'
</script>

<template>

  <Header  />
  <SectionHero  />
  <SectionServices></SectionServices>
  <SectionChoseUs/>
  <SectionClients />
  <SectionBudget />
  <Footer />
</template>

<style scoped>
  
  
</style>
