<script>
  export let src;
  export let title;
</script>

<article>
  <img {src} alt={title} />
  <h2>{title}</h2>
</article>

<style>
  article {
    display: flex;
    margin: 0.5rem 0rem;
    padding: 1rem 5rem;
    align-items: center;
  }
  h2 {
    padding: 0rem 2rem;
  }
  img {
    width: 30px;
  }
</style>
