<template>
  <div>
    <slot :user="user"></slot>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      user: {
        name: "john",
        age: 25,
      },
      favotites: ["Pizza", "Marbles", "Birds"],
    };
  },
};
</script>
