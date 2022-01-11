<template>
    <div class="flex justify-center items-center md:max-w-xs flex-col">
        <img :src=this.props.icon />
        <h1 class="font-heading font-bold text-white pt-8 text-lg text-center">{{this.props.title}}</h1>
        <p class="text-center text-purple text-sm pt-3">{{this.props.text}}</p>
    </div>
</template>

<script lang="ts" setup>
import { defineProps } from "vue";

const props = defineProps({
    title: String,
    icon: String,
    text: String,
});


</script>