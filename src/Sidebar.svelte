<script>
  import User from "./User.svelte";
  import Links from "./Links.svelte";
  import Ad from "./Ad.svelte";
</script>

<section>
  <User src="./images/brad.jpg" name="Brad Mehder" title="Web Developer" />
  <Links />
  <Ad
    title="You don't want to miss out."
    src="https://ps.w.org/shortpixel-image-optimiser/assets/icon-256x256.png"
  />
</section>

<style>
  section {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-evenly;
    padding: 2rem 0;
    text-align: center;
    background: linear-gradient(
      to right bottom,
      rgba(255, 255, 255, 0.7),
      rgba(255, 255, 255, 0.3)
    );
    border-top-left-radius: 2rem;
    border-bottom-left-radius: 2rem;
  }
</style>
