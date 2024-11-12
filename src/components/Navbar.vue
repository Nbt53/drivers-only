<template>
  <nav class="nav">
    <navbar-item itemName="Route Atelier" icon="lists_view_icon" />
    <navbar-item itemName="Your Library" icon="library_view_icon" />
    <navbar-item itemName="Tours" icon="tours_view_icon" />
    <navbar-item itemName="Arrange" icon="arrange_view_icon" />
  </nav>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import NavbarItem from "./NavbarItem.vue";

export default defineComponent({
  name: "NavbarComponent",
  components: {
    NavbarItem,
  },
  setup() {
    return {};
  },
});
</script>

<style>
nav {
  height: 79px;
  box-shadow: 0 10px 20px 0 rgba(0, 0, 0, 0.1);
}

.nav {
  display: flex;
  justify-content: space-around;
  align-items: center;
  background-color: #ffffff;
  position: fixed;
  bottom: 0;
  width: 100%;
  z-index: 100;
}
</style>