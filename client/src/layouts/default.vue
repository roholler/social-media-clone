<template>
  <v-app>
    <v-layout>
      <Sidebar> </Sidebar>
      <v-main>
        <router-view />
      </v-main>
    </v-layout>
    <AppFooter />
  </v-app>
</template>

<script lang="ts" setup>
import Sidebar from "@/components/Sidebar.vue";
//
</script>
