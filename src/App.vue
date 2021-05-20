<template>
  <div>
    <Home></Home>
  </div>
</template>
<script>
import Home from "./ccomponents/Home/Home.vue";
export default {
  components: {
    Home,
  },
  data() {
    return {
      text: "welcome to vue.js",
    };
  },
};
</script>

<style lang="scss" scoped>
#main {
  color: red;
}
</style>
