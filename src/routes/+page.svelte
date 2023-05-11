<script>
  import About from "./about/+page.svelte";
  import Appointment from "./appointment/+page.svelte";
  import Contact from "./contact/+page.svelte";
  import Cta from "./cta/+page.svelte";
  import Hero from "./hero/+page.svelte";
</script>

<svelte:head>
  <title>Home</title>
  <meta name="description" content="PSICO INSTITUCIONAL" />
</svelte:head>

<main>
  <Cta />
  <Hero />
  <About />
  <Appointment />
  <Contact />
</main>
