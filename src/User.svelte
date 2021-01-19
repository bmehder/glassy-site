<script>
  export let name;
  export let title;
  export let src;
</script>

<div class="user">
  <img {src} alt={name} />
  <h3>{name}</h3>
  <p>{title}</p>
</div>

<style>
  img {
    border-radius: 50%;
  }
</style>
