<script setup>
import {RouterView } from 'vue-router'
import HeaderIndexApp from "@/components/commun/HeaderIndexApp/HeaderIndexApp.vue";
import FooterApp from "@/components/commun/FooterApp/FooterApp.vue";
</script>

<template>
  <h1>Structure de l'app</h1>
  <HeaderIndexApp />
  <FooterApp />
  <RouterView />
</template>

<style scoped>

</style>
