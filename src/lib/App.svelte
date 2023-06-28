<script>
  import Card from "./Card.svelte";
  import Header from "./Header.svelte";

</script>

<div class="page">
  <Header />
  <Card />
</div>

<style>
  .page {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 4.5rem 2rem 3.875rem 2rem;
    background: var(--color-light-blue);
  }
</style>
