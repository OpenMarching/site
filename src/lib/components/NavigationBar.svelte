<script>
  import Logo from "$lib/components/Logo.svelte";
  import Icon from "@iconify/svelte";
</script>

<div
  class="flex flex-col w-full items-center justify-center bg-base-100 group relative">
  <div class="bg-base-100 h-4 w-96 absolute top-0 z-20"></div>
  <div
    class="p-4 bg-base-300 mt-4 rounded-2xl z-30 flex flex-row items-start relative gap-2">
    <Logo size={48} />
    <h1 class="text-4xl font-montserrat font-medium w-full text-center">
      OpenMarching
    </h1>
    <div class="absolute -bottom-2 left-0 right-0 items-center flex justify-center">
      <Icon icon="lucide:more-horizontal" width="48" height="48" />
    </div>
  </div>
  <!-- <Icon icon="lucide:menu" width="48" height="48" /> -->
  <!-- <div
    class="bg-base-300 p-1 w-24 rounded-b-2xl absolute -bottom-8 flex items-center justify-center">
    <Icon icon="lucide:more-horizontal" width="24" height="24" />
  </div> -->
  <div
    class="bg-base-100 p-1 w-96 rounded-b-2xl h-4 absolute bottom-0 group-hover:-bottom-4 text-center">
  </div>
  <div class="relative w-96 z-10">
    <div
      class="absolute flex flex-col group-hover:top-2 -top-96 transition-all bg-base-300 w-96 p-2 rounded-2xl gap-2">
      <a href="/" class="btn font-montserrat font-normal text-lg">Home</a>
      <a href="/dotflow" class="btn font-montserrat font-normal text-lg"
        >DotFlow</a>
      <!-- <a href="/tabulation" class="btn font-montserrat font-normal text-lg">Tabulation</a> -->
      <a href="/about" class="btn font-montserrat font-normal text-lg">About</a>
    </div>
  </div>
</div>
