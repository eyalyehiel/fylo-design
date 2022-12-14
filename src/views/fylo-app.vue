<template>
    <section class="main-layout">
        <hero-view />
        <features-view />
        <productive-view />
    </section>
</template>

<script>
import heroView from "../cmps/hero.vue";
import featuresView from "../cmps/features.vue";
import productiveView from '../cmps/productive.vue'
export default {
    components: {
        heroView,
        featuresView,
        productiveView
    },
};
</script>

<style lang="scss" scoped></style>
