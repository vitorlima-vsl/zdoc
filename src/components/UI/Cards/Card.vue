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
                    <div class="size-20 bg-blue-lighter flex items-center justify-center p-1 rounded-2xl mb-4"> <img class="size-12" :src="'/imagens/' + img" alt=""> </div>
                    <h3 class="text-2xl font-semibold ">{{title}}</h3>
                    <p :title="paragraph"
                        class=" text-gray-500 line-clamp-5 text-xl my-2">{{ paragraph }}
                    </p>
                </div>
                <a class="text-blue-lighter hover:text-blue-lighterHover font-medium text-xl transition-colors duration-150"
                    href="#">Saiba Mais -></a>
    </article>
</template>