<template>
  <header class="header bg-blue-800 columns-3 py-2 px-5 flex items-center">
    <div class="w-full h-12">
      <NuxtLink to="/">
        <img class="h-full" src="~/assets/img/lego.svg" />
      </NuxtLink>
    </div>
    <div class="w-full text-white hover:underline">
      <NuxtLink to="/about">
        About
      </NuxtLink>
    </div>
    <div class="w-full"></div>
  </header>
</template>

<script>
export default {

}
</script>

<style>

</style>