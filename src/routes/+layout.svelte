<script>
  import NavigationBar from "./../lib/components/NavigationBar.svelte";
  import "../app.css";
</script>

<NavigationBar />

<div class="flex flex-col pt-32 pb-8 h-full w-full items-center justify-center overflow-y-auto">
  <slot />
</div>

<div class="absolute bottom-0 w-full text-center bg-base-100">
  <p class="font-montserrat text-md font-medium">
    © Copyright OpenMarching 2024
  </p>
</div>
