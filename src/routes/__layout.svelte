<script>
    import global from "../global.css";
    import Header from "../components/Header.svelte";
    import Footer from "../components/Footer.svelte";
</script>
<svelte:head>
  <title>Amatorios</title>
</svelte:head>
<Header />
<main>
  <slot />
</main>
<Footer />
<style>
  main {
    height: 70vh;
    padding: 0 10vw;
    align-items: center;
    justify-content: center;
    display: flex;
    flex-direction: column;
  }
</style>