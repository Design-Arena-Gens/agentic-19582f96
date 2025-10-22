<script>
  let name = 'World';
</script>

<main>
  <h1>Hello {name}!</h1>
  <p>Welcome to Svelte</p>
</main>

<style>
  main {
    text-align: center;
    padding: 2rem;
    max-width: 800px;
    margin: 0 auto;
  }

  h1 {
    color: #ff3e00;
    font-size: 4rem;
    font-weight: 100;
    margin: 2rem 0;
  }

  p {
    font-size: 1.5rem;
    color: #666;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
