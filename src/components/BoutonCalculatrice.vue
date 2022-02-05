<template>
  <button @click="sendValue(value)">{{ value }}</button>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  props: {
    value: {
      type: [String, Number],
      default: 0,
    },
  },
  emits: ["send-value"],
  methods: {
    sendValue(val) {
      this.$emit("send-value", val);
    },
  },
});
</script>

<style scoped>
button {
  width: 50px;
}
</style>
