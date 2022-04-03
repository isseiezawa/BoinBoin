<template>
  <div id="app">
    <p>{{ number }}</p>
  <button @click="countUp">ここ</button>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      message: "HelloVue!",
      number: 0
    }
  },
  methods: {
    countUp: function() {
      this.number += 1
    }
  }
}
</script>

<style scoped>
p {
  font-size: 2em;
  text-align: center;
}
</style>
