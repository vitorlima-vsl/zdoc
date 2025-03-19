<script setup lang="ts">
import HiddenTittle from '../Titles/HiddenTittle.vue';
import Subtitle from '../Titles/Subtitle.vue'


</script>

<template>
    <section class="w-[1400px]  mx-auto mb-12 relative pt-14">
        <HiddenTittle color="BLACK" title="Nossos Clientes" />

        <div class="mb-12">
            <Subtitle class="mt-4" title="Nossos Clientes" />
            <h2 class="text-6xl font-bold">Trabalhe Conosco<br><span class="text-blue-lighter">Trabalhamos com os Melhores</span></h2>
        </div>

        <div class="flex justify-center w-full gap-12">

            <img class="w-36 h-[100px]" src="/imagens/clients/celi_logo.png" alt="">
            
            <img class="h-[100px]" src="/imagens/clients/hnsc_logo.png" alt="">
            
            <img class="h-[100px] " src="/imagens/clients/pierete_logo.png" alt="">
            
            <img class=" h-[100px] " src="/imagens/clients/banese_logo.png" alt="">
            
        </div>

    </section>

</template>

<style scoped></style>