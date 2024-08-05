<script>
  import NavigationBar from "./../lib/components/NavigationBar.svelte";
  import "../app.css";
</script>

<div class="flex flex-col w-full h-full">
  <NavigationBar />

  <div
    class="flex flex-col h-full w-full items-center justify-center overflow-hidden">
    <slot />
  </div>

  <div class="w-full text-center bg-base-200">
    <p class="font-montserrat text-md font-medium">
      © Copyright OpenMarching 2024
    </p>
  </div>
</div>
