<script setup lang="ts">
import HiddenTittle from '../Titles/HiddenTittle.vue';
import Subtitle from '../Titles/Subtitle.vue'
import Card from '../UI/Cards/Card.vue'

</script>

<template>
    <section class="w-[1400px]  mx-auto mb-12 relative pt-14">
       <HiddenTittle color="BLACK" title="Nossos Serviços" />

        <div class="mb-12">
            <Subtitle class="mt-4" title="Nossos Serviços" />
            <h2 class="text-6xl font-bold">Serviços Que Provemos Para <br><span class="text-blue-lighter">Melhorar o Seu
                    Negócio</span></h2>
        </div>
        
        <div class="flex justify-center w-full gap-12">
          
                <Card paragraph="Perdendo documentos e não sabe como armazená-los?
            Deixe a Zdoc gerir seus documentos e foque no que é essencial para você!
            Poupe tempo, evite prejuízos e otimize a gestão de documentos.
            Ganhe em rapidez, qualidade e eficiência no trabalho, enquanto cuidamos da organização para você."
                    title="Gestão de Documentos"
                    img="monitorDoc.png" />
            
              
            
            <Card paragraph="Análise de Sistemas, Administração de Banco de Dados, 
                        Administração de Redes, Desenvolvimento de Sistemas (Programação), Teste de Softwares…"
                        title="Tecnologia da Informação"
                        img="webDev.png" />
        </div>

    </section>

</template>

<style scoped></style>