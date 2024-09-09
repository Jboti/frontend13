<template>
  <RouterView></RouterView>
</template>


<!-- <script setup lang="ts">
import { ref } from 'vue';
import type { randomObjectType } from './app';


const dataRef = ref<number>(1);

const randomObject = ref<randomObjectType>({name:"teszt",age:10})

type UserType = {
  name: string,
  email: string,
  password: string
}

const userRef = ref<UserType>({
  name:"",
  email:"",
  password:"",
});

const usersRef = ref<UserType[]>([{
  name:"teszt elek",
  email:"tesztelek@gmail.com",
  password:"demo1234"
},
{
  name:"teszt elek",
  email:"tesztelek@gmail.com",
  password:"demo1234"
}]);

const name = ref<string>();

console.log(dataRef.value);
console.log(randomObject.value.name);
</script>



<template>
  <h1>Hello {{ dataRef }}</h1>
  <v-text-field label="Name" v-model="userRef.name"></v-text-field>

  <v-text-field label="Email" v-model="userRef.email"></v-text-field>
  <v-text-field label="Password" v-model="userRef.password"></v-text-field>
  {{ userRef }}

  <v-table>
    <thead>
      <tr>
        <th class="text-left">
          Name
        </th>
        <th class="text-left">
          email
        </th>
        <th class="text-left">
          password
        </th>
      </tr>
    </thead>
    <tbody     
        v-for="({name,email,password},index) in usersRef"
        :key="index">
      <tr
        v-if="(index == 1)"
      >
      
        <td>{{ name }}</td>
        <td>{{ email }}</td>
        <td>{{ password }}</td>
      
      </tr>
    </tbody>
  </v-table>


</template>

<style scoped>
</style> -->


