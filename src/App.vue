<template>
  <header-component></header-component>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'


export default {
  name: 'App',
  components: {
    'header-component': HeaderComponent
  }
}
</script>

<style>
@import "@/assets/css/tailwind.css";
</style>