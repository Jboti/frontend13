<script setup lang="ts">
import { useRouter } from 'vue-router';



const { back } = useRouter();

</script>

<template>
  <h1>USER CREATE</h1>
  <v-btn @click="() => {back()}">
    ugrás vissza
  </v-btn>
</template>
