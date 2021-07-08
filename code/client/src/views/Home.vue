<template>
  <div class="green"></div>
  <div class="red"></div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Home",
});
</script>

<style>
.green {
  height: 500px;
  width: 200px;
  background: rgb(204, 241, 192);
  float: left;
  /* opacity: 0; */
}
.red {
  height: 500px;
  width: 100%;
  background: rgb(243, 207, 207);
  /* float: left; */
  margin-left: 200px;
}
</style>
