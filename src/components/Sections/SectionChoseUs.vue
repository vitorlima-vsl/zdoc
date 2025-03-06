<script setup lang="ts">
import Subtitle from '../Titles/Subtitle.vue'
import HiddenTittle from '../Titles/HiddenTittle.vue'
import CardChooseUs from '../UI/Cards/CardChooseUs.vue';
</script>

<template>
    <section class="bg-blue-darker  text-white relative pb-12">
        <div class="w-[1400px]  mx-auto mt-32 flex flex-col  ">
            <div class="mb-12">
            <Subtitle class="mt-20" title="Nosso Diferencial" />
            <h2 class="text-6xl font-bold">Por quê Nos Escolher Para <br><span class="text-blue-lighter"> Resolver os Seus Problemas?</span></h2>
            <HiddenTittle color="WHITE" title="nosso diferencial" />
            </div>
            <div class="flex justify-between">
                <div class="w-[600px] ">
                    <img class="rounded-4xl" src="/imagens/fotoEquipe.jpg" alt="">
                </div>
                <div class="w-[700px] grid-cols-2 grid gap-y-4 h-[392px] p-2">     
                    <CardChooseUs title="Profissionais Qualificados" description="Nossa equipe é formada por profissionais qualificados e com vasta experiência no mercado de trabalho." icon="iconEquipePro.svg" />
                    <CardChooseUs title="Atendimento Personalizado" description="Atendemos nossos clientes de forma personalizada, entendendo suas necessidades e oferecendo soluções sob medida." icon="iconAtendimento.svg" />
                    <CardChooseUs title="Soluções Inovadoras" description="Oferecemos soluções inovadoras e tecnológicas, que visam otimizar processos e melhorar a eficiência dos negócios." icon="iconSolucao.svg" />
                    <CardChooseUs title="17+ Anos de Experiência" description="Com mais de 17 anos de experiência, somos referência no mercado de gestão de documentos e tecnologia da informação." icon="iconExperiencia.svg" />
                </div>
            </div>
        </div>
        


    </section>

</template>

<style scoped></style>