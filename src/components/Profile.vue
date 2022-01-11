<template> 
    <div class="flex text-purple font-body font-normal">
        <p>{{this.props.text}}</p>
        <div class="flex items-center flex-start">
            <img :src=this.props.img class="rounded-full"/>
            <div class="flex flex-col">
                <h1 class="text-white font-bold font-heading">{{this.props.name}}</h1>
                <h1 class="text-purple font-heading">{{this.props.job}}</h1>
            </div>
        </div>
    </div>
</template>

<script lang="ts" setup>
import { defineProps } from "vue";

const props = defineProps({
    text: String,
    img: String,
    name: String,
    job: String,
});
</script>