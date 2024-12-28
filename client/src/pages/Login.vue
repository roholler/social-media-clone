<template>
  <v-container class="d-flex align-center justify-center h-100 w-50">
    <v-form class="border rounded pa-10 w-50 d-flex flex-column">
      <h1 class="text-center mb-5">Login</h1>
      <v-text-field id="email" v-model="email" label="Email"></v-text-field>
      <v-text-field
        id="name"
        v-model="password"
        type="password"
        label="Passwort"
      ></v-text-field>
      <v-btn variant="tonal" type="submit" class="w-50 align-self-center">
        Submit
      </v-btn>
    </v-form>
  </v-container>
</template>

<script setup lang="ts">
import { ref } from "vue";
const email = ref("");
const password = ref("");
</script>

<style scoped></style>
