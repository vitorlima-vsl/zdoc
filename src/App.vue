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

  <div class="max-[1399px]:hidden">
    <Header  />
    <SectionHero  />
    <SectionServices></SectionServices>
    <SectionChoseUs/>
    <SectionClients />
    <SectionBudget />
    <Footer />
  </div>
  <div class="hidden max-[1399px]:block">
    <h3 class="text-blue-darker  text-3xl font-bold">RESPONSIVIDADE EM PROGRESSO</h3>
  </div>
 
</template>

<style scoped>
  
  
</style>
