<script setup lang="ts">
import Subtitle from '../Subtitle.vue'


</script>

<template>

    <section class="bg-blue-darker  text-white py-14">
        <div class="w-[1400px]  mx-auto mt-32 flex justify-between">
            <div class="w-[800px]"> 
                <!-- <h4><span class="text-blue-lighter mr-4">//</span>Encontre as Melhores Soluções Tecnológicas do Mercado.</h4> -->
                <Subtitle title="Encontre as Melhores Soluções Tecnológicas do Mercado."  />
                <h1 class="text-6xl font-bold mt-4">Zdoc Aonde a Criatividade Encontra-se Com a <br> Tecnologia</h1>
                <p class="text-lg mt-4">Possuímos Expertise em <span class="text-yellow">GESTÃO DE DOCUMENTOS</span> <br> e <span class="text-yellow">CONSULTORIA EM TECNOLOGIA DA INFORMAÇÃO</span></p>
                <div class="mt-8 flex gap-4">
                    <a class="bg-yellow text-gray-900 py-4 px-6  hover:bg-yellowHover transition-all duration-300" href="#">Saiba Mais</a>
                    <a class=" text-white py-4 px-6  transition-all hover:bg-white/10
                    relative
                    after:absolute after:bottom-0 after:left-0 after:w-1/3 after:h-[1.5px] after:bg-yellow hover:after:w-full after:transition-all after:ease-out after:duration-300
                    
                    " href="#">Ver Todos Projetos</a>
                </div>
            </div>
            <div class="parentSlider">
                <div class="slider " style="--width: 400px; --height:400px;
                --quantity: 6;">
                    <div class="list">
                        <div class="item " style="--position: 1;  --descricao: 'Projeto no Ar' "><img class="w-[350px]" src="/imagens/contractStep6.svg" alt=""></div>
                        <div class="item" style="--position: 2; --descricao: 'Atualização Sobre o Projeto' "> <img src="/imagens/contractStep5.svg" alt=""></div>
                        <div class="item" style="--position: 3; --descricao: 'Direcionamento ao Público Alvo' "><img src="/imagens/contractStep4.svg" alt=""></div>
                        <div class="item" style="--position: 4; --descricao: 'Pesquisa de Mercado'  "><img src="/imagens/contractStep3.svg" alt=""></div>
                        <div class="item" style="--position: 5;--descricao: 'Alinhamento Contratual' "><img src="/imagens/contractStep2.svg" alt=""></div>
                        <div class="item " style="--position: 6;--descricao: 'Entendendo o Seu Problema' "><img src="/imagens/contractStep1.svg" alt=""></div>
                    </div>
                </div>
         </div>

        </div>
    </section>


</template>

<style scoped>

.heroImage{
    background-size: cover;
    background-position: center;
}
.parentSlider{
    width: 600px;
    height: 504px;
    position: relative;
    /* border: 1px solid red; */

}
.slider{
    overflow: hidden;
    width: 600px;
    height: 624px;
    /* border: 3px solid rgb(23, 13, 114); */
    position: absolute;
    bottom: -120px;
    /* height: var(--height); */


}
.slider .list{
    
    display: flex;
    width: 100%;
    min-width: calc(var(--width) * var(--quantity));
    position: relative;
 
}
.slider .list .item{
    width: var(--width);
    height: var(--height);
    position: absolute;
    left: 100%;
    animation: autoRun 36s infinite linear;
    
    animation-delay: calc((36s / var(--quantity)) * (var(--position) - 1) * -1);
}
.slider .list .item::after{
    position: absolute;
    content: var(--descricao);
    font-size: 1.125rem;
    color: var(--color-yellow);
            font-size: 28px;
            font-weight: bold;
            margin-left: 5px;
}
.slider .list .item::after:nth-child(2n){
    /* background-color: brown; */
    bottom: 0;
}
.slider .list .item::after:nth-child(2n+1){
    /* background-color: brown; */
    top: 0;
}
.slider .list .item:nth-child(2n) {
    /* background-color: brown; */
    transform: translate(0, 45%);
}
.slider .list .item:nth-child(2n+1) {
    /* background-color: rgb(207, 123, 123); */
    transform: translate(0, 0);
}
.slider .list .item img{
    width: 100%;
    position: absolute;
    bottom:0;
}
@keyframes autoRun{
    0%{
        left: 100%;
    }
    100%{
        left: calc(var(--width) * -1);
    }
}



</style>
