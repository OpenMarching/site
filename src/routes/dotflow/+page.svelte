<script>
  import Icon from "@iconify/svelte";
  import Logo from "$lib/components/Logo.svelte";
</script>

<div class="flex flex-col w-full h-full items-center justify-center gap-2">
  <div class="flex flex-col p-4 card bg-base-300 gap-4">
    <div class="flex flex-row justify-end items-end gap-8">
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
    <div class="flex flex-row gap-4 w-full items-end justify-end">
      <div role="alert" class="alert alert-info p-1">
        <Icon icon="lucide:info" width="24" height="24" />
        <span>Early Development Status.</span>
      </div>
    </div>
  </div>
</div>
