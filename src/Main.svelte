<script>
  import Input from "./Input.svelte";
  import Cards from "./Cards.svelte";

  export let title;
</script>

<section>
  <article>
    <h1>{title}</h1>
    <Input />
  </article>
  <Cards />
</section>

<style>
  section {
    flex: 2;
    margin: 5rem;
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
  }

  article {
    margin-bottom: 3rem;
  }
</style>
