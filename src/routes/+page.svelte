<script>
  import { initializeApp } from "@firebase/app";
  import { initializeAuth } from "@firebase/auth";
  import { onMount } from "svelte";

  onMount(() => {
    const app = initializeApp({});
    initializeAuth(app);
  });
</script>

<h1>Welcome to SvelteKit</h1>
<p>
  Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation
</p>
