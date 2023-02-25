<template>
  <div class="home container mt-4 py-6">
    <img alt="Vue logo" src="../assets/logo.png" />
    <p>
      <HelloWorld msg="Weaboo Views" />
    </p>
  </div>
</template>
<style>
.home {
  text-align: center;
  margin-top: 6rem;
}
</style>
<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
  },
};
</script>
