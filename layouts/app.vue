<template>
  <div class="flex h-screen md:flex-row flex-col ">
    <div class="w-72 hidden md:flex h-full bg-gray-100">

    </div>

    <div class="py-10  px-20">
      <h1 class="font-bold text-4xl">Topics <breakpoint-detector v-if="false" /> </h1>
    </div>
    <div class="md:hidden mt-auto flex w-full bg-gray-100 h-16" ></div>
  </div>
</template>
<script>
export default {

}
</script>
<style>
@import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.5.0/font/bootstrap-icons.css");
body {
  @apply overscroll-none
}
</style>
