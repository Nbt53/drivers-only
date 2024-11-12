<template>
  <ion-app>
    <ion-router-outlet />
    <navbar />
  </ion-app>
</template>

<script lang="ts">
import Navbar from "./components/Navbar.vue";

export default {
  components: {
    Navbar,
  },
};
</script>
