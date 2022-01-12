<template>
    <div class="flex justify-center items-center md:max-w-xs flex-col">
        <img :src=icon />
        <h1 class="font-heading font-bold text-white pt-8 text-lg text-center">{{title}}</h1>
        <p class="text-center text-purple text-sm pt-3">{{text}}</p>
    </div>
</template>

<script lang="ts" setup>
const props = defineProps({
    title: String,
    icon: String,
    text: String,
});


</script>