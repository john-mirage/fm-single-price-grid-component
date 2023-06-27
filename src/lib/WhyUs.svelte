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
    background: #2AB3B1;
  }
  .overlay {
    position: absolute;
    inset: 0;
    z-index: 10;
    opacity: 0.15185546875;
    background: var(--white, #FFF);
  }
  .title {
    position: relative;
    z-index: 20;
    margin-bottom: 1.13rem;
    color: var(--white, #FFF);
    font-size: 1.125rem;
    font-family: Karla;
    font-weight: 700;
    line-height: 1.3125rem;
    letter-spacing: -0.01406rem;
  }
  .subtitle {
    position: relative;
    z-index: 20;
    color: var(--white, #FFF);
    font-size: 0.875rem;
    font-family: Karla;
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