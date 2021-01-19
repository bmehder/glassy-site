<script>
  export let top;
  export let right;
  export let bottom;
  export let left;
</script>

<div style="top:{top}; right:{right}; bottom:{bottom}; left:{left};" />

<style>
  div {
    position: absolute;
    width: 10rem;
    height: 10rem;
    background: linear-gradient(
      to right bottom,
      rgba(255, 255, 255, 0.8),
      rgba(255, 255, 255, 0.3)
    );
    border-radius: 50%;
  }
</style>
