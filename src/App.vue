<template>
  <div>
    <h1>Vue JS</h1>
    <CarOptions />
    <hr/>
    <CarComposition />
  </div>
</template>

<script>
import CarComposition from "./components/CarComposition.vue";
import CarOptions from "./components/CarOptions.vue";


export default {
  components: {
    CarOptions,
    CarComposition
  },
};
</script>

<style lang=""></style>
