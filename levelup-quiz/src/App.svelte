<script>
  import Quiz from "./Quiz.svelte";
</script>

<style>
  :global(body) {
    background: #524763;
  }

  h1 {
    color: white;
    text-align: center;
  }

  div {
    background: white;
    border-radius: 15px;
    padding: 40px;
  }
</style>

<main>
  <h1>Level Up Games</h1>
  <div>
    <Quiz />
  </div>
</main>
