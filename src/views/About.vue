<template>
  <div class="about">
    <h1>This is an about page</h1>
    <button @click="greet">greet</button>
  </div>
</template>
<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "About",
  methods: {
    greet() {
      const display = (str: string): void => {
        alert(str);
      };
      display("can i alert with ie11???");
    }
  }
});
</script>
