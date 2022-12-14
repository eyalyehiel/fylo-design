<template>
    <app-header />
    <fylo-app />
</template>

<script>
import appHeader from "./cmps/app-header.vue";
import fyloApp from './views/fylo-app.vue'
export default {
    components: {
        appHeader,
        fyloApp
    },
};
</script>
