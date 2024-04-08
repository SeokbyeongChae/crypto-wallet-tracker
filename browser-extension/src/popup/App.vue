<template>
  <v-app>
    <hello-world />
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "App",
  components: { HelloWorld }
};
</script>

<style>
html {
  width: 400px;
  height: 400px;
}
</style>
