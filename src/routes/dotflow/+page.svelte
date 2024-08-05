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
      <a href="https://github.com/openmarching/dotflow" target="_blank" class="btn">
        <Icon icon="lucide:github" width="24" height="24" color="white" />
      </a>
    </div>
    <ul class="list-disc list-outside pl-4">
      <li class="font-montserrat font-medium">Free Forever</li>
      <li class="font-montserrat font-medium">Full 3D Editor</li>
      <li class="font-montserrat font-medium">Realtime Playback</li>
      <li class="font-montserrat font-medium">Exporting</li>
      <li class="font-montserrat font-medium ml-4">Show Video with Audio</li>
      <li class="font-montserrat font-medium ml-4">Group Form</li>
      <li class="font-montserrat font-medium ml-4">
        Individual Performer Sheets
      </li>
      <li class="font-montserrat font-medium">
        Fully Extendable With Custom Lua API
      </li>
      <li class="font-montserrat font-medium ml-4">Extended Editor Plugins</li>
      <li class="font-montserrat font-medium ml-4">2D & 3D Environments</li>
      <li class="font-montserrat font-medium ml-4">
        Editor Grid and Landmarks
      </li>
      <li class="font-montserrat font-medium ml-4">
        Grid To Human Landmark Translation
      </li>
      <li class="font-montserrat font-medium">Built With Godot</li>
      <li class="font-montserrat font-medium">Open Source - MIT License</li>
    </ul>
  </div>
</div>
