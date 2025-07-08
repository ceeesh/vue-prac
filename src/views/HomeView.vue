<script setup>
import Hero from '@/components/Hero.vue';
import HomeCards from '@/components/HomeCards.vue';
import Joblistings from '@/components/Joblistings.vue';
</script>

<template>
    <Hero title="Become a Vue Dev" subtitle="'Find the Vue job that fits your skills and needs" />
    <HomeCards />
    <Joblistings :limit="3" :showButton="true" />
</template>