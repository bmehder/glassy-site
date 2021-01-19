<script>
  import Circle from "./components/Circle.svelte";
  import Sidebar from "./layout/Sidebar.svelte";
  import Main from "./layout/Main.svelte";
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
    max-width: 1024px;
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

  @media (max-width: 480px) {
    section {
      flex-direction: column;
      margin: 0;
    }
  }
</style>
