<template>
  <div>
    <span>{{ name }}</span>
  </div>
</template>

<script>
export default {
  name: "board-card",
  props: {
    id: String,
    name: String,
  },
};
</script>

<style></style>
