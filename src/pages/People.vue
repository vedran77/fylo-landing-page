<template>
    <div class="bg-dark pt-32">
        <div class="container mx-auto">
            <div class="relative">
                <img class="absolute" src="../assets/home/bg-quotes.png" alt="quote"/>
            </div>
            <div class="flex sm:flex-col md:flex-row pt-8 pb-16 pl-2 z-30">
                <Profile 
                    img="https://raw.githubusercontent.com/vedran77/fylo-landing-page/main/src/assets/home/profile-1.jpg"
                    text="Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-oiled collaboration machine."
                    name="Satish Patel"
                    job="Founder & CEO, Huddle"
                    class="md:mr-20 md:mt-0 z-10"/>

                <Profile 
                    img="https://raw.githubusercontent.com/vedran77/fylo-landing-page/main/src/assets/home/profile-2.jpg"
                    text="Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-oiled collaboration machine."
                    name="Bruce McKenzie"
                    job="Founder & CEO, Huddle"
                    class="md:mr-20 md:mt-0 sm:mt-16"/>

                <Profile 
                    img="https://raw.githubusercontent.com/vedran77/fylo-landing-page/main/src/assets/home/profile-3.jpg"
                    text="Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-oiled collaboration machine."
                    name="Iva Boyd"
                    job="Founder & CEO, Huddle"
                    class="md:mr-20 md:mt-0 sm:mt-16"/>
            </div>
        </div>
        <EarlyAccess/>
    </div>
</template>

<script setup>
import Profile from "../components/Profile.vue";
import EarlyAccess from "../components/EarlyAccess.vue";
</script>