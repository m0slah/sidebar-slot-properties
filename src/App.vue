<template>
  <HelloWorld v-slot="v">
    <p>Hello {{ v.user.name }}</p>
  </HelloWorld>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  components: {
    HelloWorld,
  },
};
</script>
