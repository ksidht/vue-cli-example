<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>{{ price }}</h2>
    <button @click="clicking()">Change Price</button>
  </div>
</template>

<script>
export default {
  name: 'Ethereum',
  props: {
    msg: String
  },
  data () {
    return {
      price: 200
    }
  },
  methods: {
    clicking () {
      this.price += 300
    }
  }
}
/* eslint-disable */
</script>