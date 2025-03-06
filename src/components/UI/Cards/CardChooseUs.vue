<script setup lang="ts">
defineProps<{
    title: string
    description: string
    icon: string
}>()
</script>

<template>
    <article class="flex flex-col gap-4 w-[300px]">
        <img class="size-16" :src="'/imagens/' + icon" alt="">
        <h3 class="text-blue-lighter text-xl font-semibold">{{ title }}</h3>
        <p :title=" description " class="text-gray-500 line-clamp-2 text-xl">{{ description }}</p>
    </article>
</template>