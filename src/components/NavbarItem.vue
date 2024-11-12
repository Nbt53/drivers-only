<template>
  <div class="nav-item">
    <div class="nav-item__icon">
      <img :src="`src/assets/icons/bottom_nav/${icon}.png`" alt="" />
    </div>
    <span class="nav-item__name"> Route Atelier </span>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "NavbarItemComponent",
  props: {
    itemName: String,
    icon: String,
  },
  setup() {
    return {};
  },
});
</script>

<style scoped>
img {

  height: 38px;
}

</style>