<script lang="ts">
  import Navbar from "./lib/Navbar.svelte";
  import About from "./lib/About.svelte";
  import Jokes from "./lib/Jokes.svelte";
  import Projects from "./lib/Projects.svelte";
  import Contacts from "./lib/Contacts.svelte";
</script>

<main class="App">
  <Navbar />

  <div class="home">
    <About />

    <Jokes />

    <Projects />

    <Contacts />
  </div>
</main>
