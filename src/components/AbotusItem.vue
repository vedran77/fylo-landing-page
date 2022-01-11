<template>
    <div class="flex justify-center items-center max-w-xs flex-col">
        <img :src=this.props.icon />
        <h1>{{this.props.title}}</h1>
        <p>{{this.props.text}}</p>
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