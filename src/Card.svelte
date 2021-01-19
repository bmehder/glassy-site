<script>
  export let src;
  export let title;
  export let subtitle;
  export let progress;
</script>

<article>
  <img {src} alt={title} />
  <div>
    <h2>{title}</h2>
    <p>{subtitle}</p>
    <progress value={progress} max="100" />
  </div>
  <h3>{progress}%</h3>
</article>

<style>
  article {
    display: flex;
    width: 100%;
    background: linear-gradient(
      to left top,
      rgba(255, 255, 255, 0.8),
      rgba(255, 255, 255, 0.5)
    );
    border-radius: 1rem;
    margin: 2rem 0rem;
    padding: 2rem;
    box-shadow: 6px 6px 20px rgba(122, 122, 122, 0.212);
    justify-content: space-between;
    gap: 2rem;
  }

  img {
    width: 100px;
    height: 100px;
    object-fit: cover;
  }

  progress {
    background: linear-gradient(to right top, #65dfc9, #6cdbeb);
    width: 100%;
    height: 25%;
    border-radius: 1rem;
  }
  progress[value]::-webkit-progress-value {
    background-color: #6cdbeb;
    border-radius: 2px;
  }
  div {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    width: 100%;
  }

  h3 {
    flex: 1;
    font-weight: bold;
    color: #6cdbeb;
  }
</style>
