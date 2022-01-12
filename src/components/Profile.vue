<template> 
    <div class="flex text-purple font-body font-normal max-w-7x1 flex-col bg-lightdark p-5">
        <p>{{this.props.text}}</p>
        <div class="flex flex-row mt-8">
            <img :src=this.props.img width="40" height="40" class="rounded-full" />
            <div class="flex flex-col ml-4">
                <h1 class="text-white font-bold font-heading">{{this.props.name}}</h1>
                <h1 class="text-purple font-heading font-bold text-xs">{{this.props.job}}</h1>
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