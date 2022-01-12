<template> 
    <div class="flex text-purple font-body font-normal max-w-full flex-col bg-lightdark p-5">
        <p class="text-xs">{{text}}</p>
        <div class="flex flex-row mt-8">
            <img :src=img width="40" height="40" class="rounded-full" />
            <div class="flex flex-col ml-4">
                <h1 class="text-white font-bold font-heading sm:text-xs md:text-base">{{name}}</h1>
                <h1 class="text-purple font-heading font-bold text-xs">{{job}}</h1>
            </div>
        </div>
    </div>
</template>

<script lang="ts" setup>
const props = defineProps({
    text: String,
    img: String,
    name: String,
    job: String,
});
</script>