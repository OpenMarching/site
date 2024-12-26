<script lang="ts">
  import tilt from "$lib/tilt";
  import Icon from "@iconify/svelte";
  import Logo from "$lib/components/Logo.svelte";
</script>

<div class="flex flex-col w-full h-full items-center justify-center gap-8">
  <div use:tilt={{ scale: 1.1, reverse: true }}>
    <Logo size={256} />
  </div>
  <a
    href="/dotflow"
    class="flex flex-col p-4 card bg-base-300 gap-4 relative w-auto hover:shadow-2xl hover:scale-105 transition-all">
    <div class="flex flex-row justify-around items-end gap-8">
      <Logo size={96} logo="dotflow" />
      <div class="flex flex-col h-full items-end justify-between">
        <h1 class="text-4xl font-montserrat font-medium w-full">DotFlow</h1>
        <ul class="list-disc list-inside">
          <li class="font-montserrat font-medium text-sm">Open Source</li>
          <li class="font-montserrat font-medium text-sm">Built for the Web</li>
          <li class="font-montserrat font-medium text-sm">Free Forever</li>
        </ul>
      </div>
    </div>
    <div
      class="absolute bg-info p-1 rounded-full -top-4 -right-4 tooltip tooltip-info tooltip-left"
      data-tip="Early Development Status">
      <Icon icon="lucide:info" width="24" height="24" color="black" />
    </div>
  </a>
</div>
