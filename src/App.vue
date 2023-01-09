<script setup>
import DcHeader from './components/DcHeader.vue';
import DcMain from './components/DcMain.vue';
import DcFooter from './components/DcFooter.vue';
</script>

<template>

  <DcHeader />
  <DcMain />
  <DcFooter />

</template>

<style lang="scss">
@use './styles/general.scss' as *;
@use './styles/partials/variables.scss' as *;
@use '../node_modules/bootstrap/scss/bootstrap.scss' as *;
</style>
