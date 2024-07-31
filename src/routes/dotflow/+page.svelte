<script>
  import Icon from "@iconify/svelte";
  import Logo from "$lib/components/Logo.svelte";
</script>

<div
  class="flex flex-col w-auto h-full items-center justify-center gap-0 max-w-96 m-auto">
  <div class="flex flex-col p-4 card bg-base-300 gap-4 relative w-96">
    <div class="flex flex-row justify-around items-end gap-8">
      <Logo size={128} />
      <div class="flex flex-col h-full items-end justify-between">
        <h1 class="text-4xl font-montserrat font-medium w-full">DotFlow</h1>
        <ul class="list-disc list-inside">
          <li class="font-montserrat font-medium">Open Source</li>
          <li class="font-montserrat font-medium">Powered By Godot</li>
          <li class="font-montserrat font-medium">Free Forever</li>
        </ul>
      </div>
    </div>
    <div
      class="absolute bg-info p-2 rounded-full -top-4 -right-4 tooltip tooltip-info tooltip-left"
      data-tip="Early Development Status">
      <Icon icon="lucide:info" width="24" height="24" color="black" />
    </div>
  </div>
  <div class="flex flex-col p-4 gap-4 relative w-full">
    <ul class="list-disc list-outside pl-4">
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
    </ul>
  </div>
</div>
