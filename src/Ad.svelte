<script>
  export let title;
  export let src;
</script>

<div>
  <h2>{title}</h2>
  <img {src} alt={title} />
</div>

<style>
  div {
    position: relative;
    margin: 0 2rem;
    padding: 1rem;
    background: linear-gradient(to right top, #65dfc9, #6cdbeb);
    border-radius: 2rem;
    color: white;
  }

  img {
    position: absolute;
    top: 5%;
    right: 10%;
    width: 120px;
    transform: rotate(32deg);
  }
  h2 {
    width: 50%;
    color: white;
    font-weight: 600;
  }
</style>
