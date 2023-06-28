<script> 
  import Cta from "./Cta.svelte";
  import WhyUs from "./WhyUs.svelte";

</script>

<main class="container">
  <div class="header">
    <h2 class="title">Join our community</h2>
    <p class="subtitle">30-day, hassle-free money back guarantee</p>
    <p class="description">Gain access to our full library of tutorials along with expert code reviews. Perfect for any developers who are serious about honing their skills.</p>
  </div>
  <div class="body">
    <Cta />
    <WhyUs />
  </div>
</main>

<style>
  .container {
    width: 100%;
    max-width: 19.4375rem;
    background: var(--color-white);
    box-shadow: 0px 15px 30px 0px rgba(0, 81, 171, 0.15);
    border-radius: 5px;
    overflow: hidden;
  }
  .header {
    padding: 1.75rem 1.5rem 2rem 1.5rem;
  }
  .title {
    margin-bottom: 1.5rem;
    color: var(--color-cyan);
    font-size: 1.25rem;
    font-weight: 700;
    letter-spacing: -0.01563rem;
    line-height: 1.4375rem;
  }
  .subtitle {
    margin-bottom: 1rem;
    color: var(--color-bright-yellow);
    font-size: 0.9375rem;
    font-weight: 700;
    line-height: 1.25rem;
    letter-spacing: -0.01169rem;
  }
  .description {
    color: var(--color-grayish-blue);
    font-size: 0.875rem;
    line-height: 1.625rem;
    letter-spacing: -0.01094rem;
  }
  @media screen and (min-width: 768px) {
    .container {
      max-width: 39.6875rem;
    }
    .header {
      padding: 2.5rem;
    }
    .body {
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
    }
    .title {
      font-size: 1.5rem;
      letter-spacing: -0.01875rem;
      line-height: 1.75rem;
    }
    .subtitle {
      font-size: 1.125rem;
      letter-spacing: -0.01406rem;
      line-height: 1.3125rem;
    }
    .description {
      font-size: 1rem;
      line-height: 1.625rem;
      letter-spacing: -0.0125rem;
    }
  }
</style>
