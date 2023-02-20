<script setup>
import {RouterView } from 'vue-router'
import HeaderApp from "@/components/commun/HeaderApp/HeaderApp.vue";
import FooterApp from "@/components/commun/FooterApp/FooterApp.vue";
</script>

<template>
  <h1>Structure de l'app</h1>
  <HeaderApp />
  <FooterApp />
  <RouterView />
</template>

<style scoped>

</style>
