<template>
  <div>

    <div class="wrapper">

    </div>
    
    <BookList :books="books" />

  </div>
</template>

<script>
    import BookList from "../components/BookList.vue"

    export default {
        name: 'catalogue-catalogue',

        components: {
            BookList
        },

        computed: {
            books() {
                return this.$root.$data.books;
            }
        },

  }
</script>

<style scoped>
    .wrapper {
        display: flex;
        align-items: center;
        justify-content: center;
        background-color: #DE6E4B;
    }
</style>
