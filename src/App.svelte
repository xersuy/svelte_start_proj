<script>
  export let name;
  import Header from "./components/header.svelte";
  import Content from "./components/Content.svelte";
  import Bottom from "./components/Bottom.svelte";
</script>

<main>
  <Header />
  <h1>Hello {name}!</h1>
  <Content />
  <Bottom />
</main>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }

  h1 {
    color: #ff3e00;
    text-transform: uppercase;
    font-size: 4em;
    font-weight: 100;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
