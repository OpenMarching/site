<script>
  import { page } from "$app/stores";
</script>

<div class="flex flex-col w-full h-full items-center justify-center gap-2">
  <p class="font-montserrat text-2xl font-bold">
    {$page.status} - {$page.error?.message}
  </p>
  <a href="/" class="btn font-montserrat">Back Home</a>
</div>
