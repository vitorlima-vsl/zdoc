<script setup lang="ts">
defineProps<{
    title: string
    paragraph: string
    img: string 
    
}>()





</script>

<template>
    <article class="w-[350px] h-[350px] bg-white p-4 rounded-2xl flex flex-col justify-between border-[1.5px] border-gray-200">
                <div class="">
                    <div class="size-20  bg-blue-darker flex items-center justify-center p-1 rounded-2xl mb-4"> <img class="size-12" :src="'/imagens/' + img" alt=""> </div>
                    <h3 class="text-2xl font-semibold ">{{title}}</h3>
                    <p :title="paragraph"
                        class=" text-gray-500 line-clamp-5 text-xl my-2">{{ paragraph }}
                    </p>
                </div>
                <div class="flex justify-start  items-center gap-3 text-blue-darker hover:text-blue-darkerHover font-medium text-2xl transition-colors duration-150">

                <a class="peer "
                    href="#">Saiba Mais  </a> 

                    <span class="transition-all duration-300 text-4xl h-[32px] flex items-center pb-1 peer-hover:pl-2">→</span>
                </div>              
    </article>
</template>