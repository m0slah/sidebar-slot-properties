<template>
  <HelloWorld #default="{ user, favotites }">
    <p>Hello {{ user.name }}</p>

    <ul>
      <li>{{ favotites }}</li>
    </ul>
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
