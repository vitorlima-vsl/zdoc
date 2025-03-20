<script setup lang="ts">
import Subtitle from "../Titles/Subtitle.vue";
import HiddenTittle from "../Titles/HiddenTittle.vue";
</script>

<template>
  <section id="section-contact" class="bg-blue-darker text-white relative pb-12">
    <div class="w-[1400px] mx-auto mt-32 flex flex-col">
      <div class="mb-12">
        <Subtitle class="mt-20" title="Contate-nos" />
        <h2 class="text-6xl font-bold">
          Entre em Contato <br /><span class="text-blue-lighter">
            Estamos aqui para ajudar!</span
          >
        </h2>
        <HiddenTittle color="WHITE" title="Contate-nos" />
      </div>
      <div class="flex gap-12">
        <address class="flex bg-blue-950 h-[500px] w-[800px] rounded-xl ">
            <div class="w-[300px] px-6">
               <h2 class="font-bold text-center text-7xl text-transparent stroke-white-zdoc mt-2">Zdoc</h2>
              <div class="flex flex-col gap-4 h-[280px] mt-4">
               <div>
                <h3 class="font-semibold ">Endereço:</h3>
                <div class="ml-2">

                    <span class="text-xs font-semibold text-gray-400">R. José Ramos da Silva, 228 - Sala 14 <br> 13 de Julho, Aracaju - SE - 49020-200</span>
                </div>
               </div>
               <div>
                    <h3 class="font-semibold ">Contato:</h3>
                    <div class="ml-2">
                            <span class="text-xs font-semibold text-gray-400">Telefone: 07932590445 <br> Email: contato@zdoc.com.br
                            </span>
                    </div>
               </div>
                <div>
                    <h3 class="font-semibold ">Funcionamento:</h3>
                    <div class="ml-2">
                        <span class="text-xs font-semibold text-gray-400">Segunda a Quinta - 08:00 - 17:00 <br> Sexta - 08:00 - 16:00</span>
                    </div>
                </div>
                <div class="">
                    <h3 class="font-semibold ">Desenvolvedor:</h3>
                    <div class="ml-2">
                        <span class="text-xs font-semibold text-gray-400">
                        <a class="text-blue-lighter hover:text-blue-lighterHover" href="https://vitorlima-vsl.github.io/vitorlima-vsl/" target="_blank" >Vitor dos Santos Lima - Front-End</a>
                    <br> Telefone: 79 9 9650-4137 <br> Email: vitorsawada2002@gmail.com <br> Portfolio: <a class="text-blue-lighter hover:text-blue-lighterHover" href="https://vitorlima-vsl.github.io/vitorlima-vsl/" target="_blank" >vitorlima-vsl</a> </span>
                    </div>
                </div>
            </div>
            </div>
            <div class=" bg-black h-full ">
                <iframe class="h-full rounded-r-xl" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3917.4360038162667!2d-37.05213672400166!3d-10.930400522122982!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x71ab2572f27dc73%3A0xca377531970e7058!2sZDoc%20-%20Tecnologia%20em%20Gest%C3%A3o%20Documental!5e0!3m2!1spt-BR!2sbr!4v1742386015788!5m2!1spt-BR!2sbr" width="500" style="border:0;" allowfullscreen></iframe>
            </div>

        </address>
       
        <form class="justify-between flex flex-col items-center" action="">
          <div class="grid grid-cols-2 gap-y-2 gap-x-6">
            <div class="flex flex-col w-[250px]">
              <label class="text-blue-lighter" for=""> Nome: </label>
              <input class="focus:outline-none border-[1px] border-blue-900 bg-blue-950 pl-3 pr-2 py-2 rounded-lg " type="text" placeholder="Ex: Vitor Lima" />
            </div>

            <div class="flex flex-col w-[250px]">
              <label class="text-blue-lighter" for=""> Email: </label>
              <input class="focus:outline-none border-[1px] border-blue-900 bg-blue-950 pl-3 pr-2 py-2 rounded-lg " type="text" placeholder="Ex: vitorsawada2002@gmail.com" />
            </div>

            <div class="flex flex-col w-[250px]">
              <label class="text-blue-lighter" for=""> Telefone: </label>
              <input class="focus:outline-none border-[1px] border-blue-900 bg-blue-950 pl-3 pr-2 py-2 rounded-lg " type="text" placeholder="Ex: 79 9 9650-4137" />
            </div>
            <div class="flex flex-col w-[250px]">
              <label class="pl-[2.5px] text-blue-lighter" for="servico"> Serviço: </label>
              <select class="focus:outline-none cursor-pointer border-[1px] border-blue-900 bg-blue-950  pl-3 pr-2 py-2 rounded-lg h-[42px] " name="servico" id="">
                <option class="text-slate-500"  value="">Escolha o serviço</option>
                <option value="ti">Tecnologia da Informação</option>
                <option value="gestaoDoc">Gestão de Documentos</option>
              </select>
            </div>
            <div class="flex flex-col col-span-2">
              <label class="text-blue-lighter" for="servico">Mensagem: </label>
              <textarea
                    class="focus:outline-none border-[1px] border-blue-900 bg-blue-950  pl-3 pr-2 py-2 rounded-lg resize-none"
                    name=""
                    id=""
                    cols="30"
                    rows="10"
                    placeholder="Digite Aqui..."
                ></textarea>
            </div>
          </div>
          <button class="bg-yellow text-blue-darker font-bold py-2 px-4 rounded hover:bg-yellowHover w-[200px] cursor-pointer">Enviar Mensagem</button>
        </form>
      </div>
    </div>
  </section>
</template>

<style scoped>

.stroke-white-zdoc {
    -webkit-text-stroke: 1px rgba(253, 245, 245, 0.795);
}


</style>
