<script setup>
import { RouterView } from "vue-router";
import HeaderComp from "./components/headerComp.vue";
</script>

<template>
  <header></header>
  <HeaderComp />
  <RouterView />
</template>

<style scoped></style>
