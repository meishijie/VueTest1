<template>
  <div class="hello1">
    <h1>{{ msg }}</h1>
    <h2>中文</h2>
  </div>
</template>

<script>
export default {
  name: 'main',
  data () {
    return {
      msg: '订单'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
