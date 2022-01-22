<template>
  <h1 style="color: #f00">Hello</h1>
  <div v-for="i in 50">
    <div v-if="i % 4 == 0" style="background-color: #ff0">{{ i }}</div>
    <div v-if="i % 4 != 0" style="background-color: #fff">labyrinth</div>
  </div>
</template>

<script>
import { defineComponent } from "vue";
import New from "./components/New.vue";

export default defineComponent({
  components: {
    New,
  },
  setup() {
    return;
  },
});
</script>

<style>
</style>