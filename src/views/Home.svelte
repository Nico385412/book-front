<script>
    import Book from '../components/Book.svelte'
</script>

<div class="home">
    <dir class="book-wrapper">
        <Book/>
        <Book/>
        <Book/>
        <Book/>
        <Book/>
        <Book/>
        <Book/>
        <Book/>
        <Book/>
        <Book/>
        <Book/>
        <Book/>
        <Book/>
    </dir>
</div>

<style>
    .home {
        display: flex;
        justify-content: center;
    }
    .book-wrapper {
        display : flex;
        flex-wrap: wrap;
        justify-content: space-evenly;
        max-width: 80em;
    }
</style>