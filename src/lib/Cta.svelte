<script>
</script>

<div class="container">
  <h2 class="title">Monthly Subscription</h2>
  <div class="row">
    <p class="price">$29</p>
    <p class="period">per month</p>
  </div>
  <p class="incentive">Full access for less than $1 a day</p>
  <button class="button">Sign Up</button>
</div>

<style>
  .container {
    padding: 1.5rem;
    background: var(--color-cyan);
    color: var(--color-white);
  }
  .title {
    margin-bottom: 1.13rem;
    font-size: 1.125rem;
    font-weight: 700;
    line-height: 1.3125rem;
    letter-spacing: -0.01406rem;
  }
  .row {
    margin-bottom: 0.25rem;
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 0.69rem;
  }
  .price {
    font-size: 2rem;
    font-weight: 700;
    line-height: 2.3125rem;
    letter-spacing: -0.025rem;
  }
  .period {
    font-size: 1rem;
    line-height: 1.625rem;
    letter-spacing: -0.0125rem;
    opacity: 0.5;
  }
  .incentive {
    margin-bottom: 1.63rem;
    font-size: 1rem;
    line-height: 1.625rem;
    letter-spacing: -0.0125rem;
  }
  .button {
    width: 100%;
    height: 3rem;
    border-radius: 5px;
    background: var(--color-bright-yellow);
    box-shadow: 0px 10px 10px 0px rgba(0, 0, 0, 0.10);
    color: var(--color-white);
    font-size: 1rem;
    font-weight: 700;
    letter-spacing: -0.0125rem;
    line-height: 1.1875 rem;
    border: none;
    cursor: pointer;
  }

  @media screen and (prefers-reduced-motion: no-preference) {
    .button {
      transition-property: box-shadow;
      transition-duration: 150ms;
    }
  }

  @media screen and (hover: hover) {
    .button:hover {
      box-shadow: 0 0 0 6px rgba(255, 255, 255, 0.2);
    }
  }

  @media screen and (min-width: 768px) {
    .container {
      padding: 2.5rem;
    }
    .title {
      font-size: 1.125rem;
      font-weight: 700;
      letter-spacing: -0.01406rem;
    }
  }
</style>