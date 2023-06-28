<script>
  const listItems = [
    "Tutorials by industry experts",
    "Peer & expert code review",
    "Coding exercises",
    "Access to our GitHub repos",
    "Community forum",
    "Flashcard decks",
    "New videos every week"
  ];
</script>

<section class="container">
  <div class="overlay"></div>
  <h2 class="title">Why Us</h2>
  <ul class="list">
    {#each listItems as item}
      <li class="list-item">{item}</li>
    {/each}
  </ul>
</section>

<style>
  .container {
    position: relative;
    padding: 1.5rem;
    background: var(--color-cyan);
    color: var(--color-white);
  }
  .overlay {
    position: absolute;
    inset: 0;
    z-index: 10;
    opacity: 0.15185546875;
    background: var(--color-white);
  }
  .title {
    position: relative;
    z-index: 20;
    margin-bottom: 1.13rem;
    font-size: 1.125rem;
    font-weight: 700;
    line-height: 1.3125rem;
    letter-spacing: -0.01406rem;
  }
  .list {
    position: relative;
    z-index: 20;
    margin: 0;
    padding: 0;
    list-style: none;
  }
  .list-item {
    font-size: 0.875rem;
    line-height: 1.25rem;
    letter-spacing: -0.01094rem;
    opacity: 0.75;
  }
  @media screen and (min-width: 768px) {
    .container {
      padding: 2.5rem;
    }
  }
</style>