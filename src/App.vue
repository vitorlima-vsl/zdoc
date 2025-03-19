<script setup lang="ts">
import Header from './components/Header/Header.vue'
import SectionHero from './components/Sections/SectionHero.vue'
import SectionServices from './components/Sections/SectionServices.vue'
import SectionChoseUs from './components/Sections/SectionChoseUs.vue'
import SectionClients from './components/Sections/SectionClients.vue'

</script>

<template>

  <Header  />
  <SectionHero key='#ect' />
  <SectionServices></SectionServices>
  <SectionChoseUs/>
  <SectionClients />
</template>

<style scoped>

</style>
