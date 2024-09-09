<script setup lang="ts">
import { useRouter } from 'vue-router';



const { push } = useRouter();

</script>

<template>
  <h1>USER LIST</h1>
  <v-btn @click="() => {push({name:'users_create'})}">
    ugrás tovább
  </v-btn>
  <v-btn @click="() => {push({name:'users_edit',params: {id: 1},query:{page:15}})}">
    ugrás id
  </v-btn>
</template>
