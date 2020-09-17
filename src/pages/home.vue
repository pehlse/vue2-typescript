<template>
  <p>{{ message }}</p>
</template>

<script lang="ts">
import Vue from "vue";
import Component from "vue-class-component";

@Component
export default class Home extends Vue {
  message = "teste";
}
</script>

<style scoped></style>
