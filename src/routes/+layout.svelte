<script>
  import NavigationBar from "./../lib/components/NavigationBar.svelte";
  import "../app.css";
</script>

<NavigationBar />

<slot />

<div class="absolute bottom-0 w-full text-center">
  <p class="font-montserrat text-md font-medium">© Copyright OpenMarching 2024</p>
</div>
