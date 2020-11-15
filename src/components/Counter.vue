<template>
  <div>
    <div>{{ count }}</div>
    <button @click="inc">+</button>
    <button @click="dec">-</button>
  </div>
</template>

<script>
export default {
  name: "counter",
  data() {
    return {
      count: 0
    };
  },
  methods: {
    inc() {
      this.count++;
    },
    dec() {
      this.count--;
    }
  }
};
</script>
