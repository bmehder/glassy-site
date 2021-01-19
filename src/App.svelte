<script>
  import Sidebar from "./Sidebar.svelte";
  import Main from "./Main.svelte";
  import Circle from "./Circle.svelte";
</script>

<main>
  <section>
    <Sidebar />
    <Main title="Preferred Technologies" />
  </section>
</main>

<Circle top="50%" left="5%" />
<Circle top="25%" right="5%" />

<style>
  main {
    font-family: "Poppins", sans-serif;
    min-height: 100vh;
    background: linear-gradient(to right top, #65dfc9, #6cdbeb);
    display: flex;
    align-items: center;
    justify-content: center;
  }

  section {
    background: white;
    margin: 2rem;
    min-height: 80vh;
    width: 1024px;
    background: linear-gradient(
      to right bottom,
      rgba(255, 255, 255, 0.7),
      rgba(255, 255, 255, 0.3)
    );
    border-radius: 2rem;
    z-index: 2;
    backdrop-filter: blur(2rem);
    display: flex;
  }
</style>
