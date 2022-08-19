<template>
  <div class="main">
    <h2>Product Review for {{ name }}</h2>
    <p class="description">{{ description }}</p>
  </div>
</template>

<script>
export default {
  name: "product-review",
  data() {
    return {
      name: "Cigar Parties for dummies",
      description: "Host and plan the perfect cigar party fpr ",
    };
  },
};
</script>

<style>
</style>