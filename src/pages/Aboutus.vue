<template>
    <div class="bg-dark pb-16">
        <div class="container mx-auto">
            <div class="flex sm:flex-col md:flex-row md:justify-center md:mt-24 msm:mt-16 md:pt-16 sm:pt-20">
                <AboutusItem 
                    icon="https://raw.githubusercontent.com/vedran77/fylo-landing-page/main/src/assets/home/icon-access-anywhere.svg" 
                    title="Access your files, anywhere" 
                    text="The ability to use a smartphone, tablet, or computer to access your account means your files follow you everywhere."
                    class="md:mr-32 sm:mb-24 md:mb-0" />

                <AboutusItem 
                    icon="https://raw.githubusercontent.com/vedran77/fylo-landing-page/main/src/assets/home/icon-security.svg" 
                    title="Security you can trust" 
                    text="2-factor authentication and user-controlled encryption are just a couple of the security features we allow to help secure your files."
                    class="md:ml-32" />
            </div>
            <div class="flex sm:flex-col md:justify-center mt-24 md:flex-row">
                <AboutusItem 
                    icon="https://raw.githubusercontent.com/vedran77/fylo-landing-page/main/src/assets/home/icon-collaboration.svg" 
                    title="Real-time collaboration" 
                    text="Securely share files and folders with friends, family and colleagues for live collaboration. No email attachments required."
                    class="md:mr-32 sm:mb-24 md:mb-0" />

                <AboutusItem 
                    icon="https://raw.githubusercontent.com/vedran77/fylo-landing-page/main/src/assets/home/icon-any-file.svg" 
                    title="Store any type of file" 
                    text="Whether you're sharing holidays photos or work documents, Fylo has you covered allowing for all file types to be securely stored and shared."
                    class="md:ml-32" />
            </div>
        </div>
    </div>
</template>

<script setup>
import AboutusItem from "../components/AbotusItem.vue";
</script>