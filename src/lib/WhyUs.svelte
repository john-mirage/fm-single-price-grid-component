<script>
</script>

<div class="container">
  <div class="overlay"></div>
  <h2 class="title">Why Us</h2>
  <p class="subtitle">Tutorials by industry experts<br>Peer & expert code review<br>Coding exercises<br>Access to our GitHub repos<br>Community forum<br>Flashcard decks<br>New videos every week</p>
</div>

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
  .subtitle {
    position: relative;
    z-index: 20;
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