<template>
  <div class="hello">
    <h1 class="display-5 mt-5">KafeinArt's Views</h1>
    <center>
      <hr width="140px" />
    </center>
    <p style="font-size: 16px">Terbuat dari ketenangan dan ekstra kafein</p>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
