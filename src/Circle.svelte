<script>
  export let top;
  export let right;
  export let bottom;
  export let left;
</script>

<article style="top:{top}; right:{right}; bottom:{bottom}; left:{left};" />

<style>
  article {
    background: white;
    background: linear-gradient(
      to right bottom,
      rgba(255, 255, 255, 0.8),
      rgba(255, 255, 255, 0.3)
    );
    height: 10rem;
    width: 10rem;
    position: absolute;
    border-radius: 50%;
  }
</style>
