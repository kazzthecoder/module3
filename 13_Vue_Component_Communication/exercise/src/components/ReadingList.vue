<template>
  <div class="book-container">
    <book-card
      v-for="book in $store.state.books"
      :key="book.title"
      v-bind:book="book"
    />
  </div>
</template>

<script>
import BookCard from "./BookCard.vue";
export default {
  components: { BookCard },
  name: "reading-list",
};
</script>

<style>
.book-container {
  display: flex;
  justify-content: space-evenly;
  flex-wrap: wrap;
}
</style>
