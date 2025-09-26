<script setup lang="ts">
import NavBar from './components/NavBar.vue'
import Carrossel from './components/FlexBox.vue'
import Titulo from './components/Titulo.vue'
import FlexBox from './components/FlexBox.vue';
import ContainerIcone from './components/ContainerIcone.vue';

</script>

<template>
     
    <router-view />
    <NavBar />
    <FlexBox />
    <ContainerIcone />

</template>

<style scoped>

</style>
