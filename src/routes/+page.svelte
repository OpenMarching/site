<script>
  import Icon from "@iconify/svelte";
  import Logo from "$lib/components/Logo.svelte";
</script>

<div class="flex flex-col w-full h-full items-center justify-center gap-2">
  <Logo size={256} />
  <h1 class="text-4xl font-montserrat font-medium">DotFlow</h1>
  <p class="text-center">The Ultimate Open Source Drill Writing Software.</p>
  <p class="text-center">Powered By Godot. Free Forever.</p>
  <div class="flex flex-row gap-4">
    <a href="/dotflow" class="btn">Learn More</a>
    <a
      href="https://github.com/OpenMarching/DotFlow"
      target="_blank"
      class="btn">
      <Icon icon="lucide:github" width="24" height="24" />
    </a>
  </div>
</div>
