<script lang="ts">
  import tilt from "$lib/tilt";
  import Icon from "@iconify/svelte";
  import Logo from "$lib/components/Logo.svelte";
</script>

<div
  class="flex flex-col w-auto items-center gap-0 max-w-96 mx-auto overflow-y-auto">
  <div
    class="flex flex-col p-4 gap-4 relative w-full items-center justify-center">
    <div
      class="absolute bg-info p-1 rounded-full top-2 right-1 tooltip tooltip-info tooltip-left"
      data-tip="Early Development Status">
      <Icon icon="lucide:info" width="24" height="24" color="black" />
    </div>
    <div
      class="flex w-64 h-64 touch-manipulation"
      use:tilt={{ scale: 1.1, reverse: true }}>
      <Logo size={256} logo="dotflow" />
    </div>
    <div class="flex flex-row w-full items-end">
      <h1 class="text-4xl font-montserrat font-medium w-full">DotFlow</h1>
      <!-- <a href="https://github.com/openmarching/dotflow" target="_blank" class="btn">
        <Icon icon="lucide:github" width="24" height="24" color="white" />
      </a> -->
    </div>
    <ul class="list-disc list-outside pl-4">
      <li class="font-montserrat font-medium">
        3D and 2D Editing Environments
      </li>
      <li class="font-montserrat font-medium">Web Based</li>
      <li class="font-montserrat font-medium">Modular and Extendable</li>
      <li class="font-montserrat font-medium">Open Source - MIT License</li>
    </ul>
  </div>
</div>
