<script setup lang="ts">
import HiddenTittle from '../Titles/HiddenTittle.vue';
import Subtitle from '../Titles/Subtitle.vue'
import Card from '../UI/Cards/Card.vue'

</script>

<template>
    <section id="section-services" class="w-[1400px]  mx-auto mb-12 relative pt-14">
        <HiddenTittle color="BLACK" title="Nossos Serviços" />

        <div class="mb-12">
            <Subtitle class="mt-4" title="Nossos Serviços" />
            <h2 class="text-6xl font-bold text-blue-lighter">Serviços Que Provemos Para <br><span class="text-blue-darker">Melhorar o Seu
                    Negócio</span></h2>
        </div>

        <div class="flex justify-center w-full gap-12">

            <Card paragraph="Perdendo documentos e não sabe como armazená-los?
            Deixe a Zdoc gerir seus documentos e foque no que é essencial para você!
            Poupe tempo, evite prejuízos e otimize a gestão de documentos.
            Ganhe em rapidez, qualidade e eficiência no trabalho, enquanto cuidamos da organização para você."
                title="Gestão de Documentos" img="monitorDoc.png" />



            <Card paragraph="Análise de Sistemas, Administração de Banco de Dados, 
                        Administração de Redes, Desenvolvimento de Sistemas (Programação), Teste de Softwares…"
                title="Tecnologia da Informação" img="webDev.png" />

            <div class="h-[350px] w-[650px] bg-blue-darker rounded-2xl flex items-center justify-center">
                <div class="size-[90%] flex flex-col justify-between">
                    <div>
                        <div class="">
                            <h3 class="text-white text-4xl font-bold">Tecnologia da Informação</h3>
                        <div class="pl-3">
                            <span class="font-semibold text-gray-400 text-xl">Desenvolvemos soluções personalizadas para atender às necessidades específicas do seu
                                negócio, garantindo eficiência, inovação e resultados concretos.</span>
                        </div>
                        </div>
                        <div class="mt-6">
                            <h3 class="text-white text-4xl font-bold">Gestão de Documentos </h3>
                            <div class="pl-3">
                            <span class="text-gray-400 font-semibold text-xl"> Gerencie seus documentos com segurança e praticidade. Otimize processos e economize tempo com nossas soluções inteligentes. </span>
                            </div>
                        </div>
                    </div>
                    <div class="w-full flex justify-end">
                        <a href="#" 
                        class=" bg-yellow text-blue-darker font-bold py-2 px-4 rounded hover:bg-yellowHover"
                        >SOLICITAR ORÇAMENTO </a>
                        
                    </div>
                </div>
            </div>
        </div>

    </section>

</template>

<style scoped></style>