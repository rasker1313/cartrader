<template>
  <div>
    <NavBar />
    <div class="mx-auto mt-4 max-w-7xl space-y-4 px-4 xs:px-8 sm:px-10 lg:px-16 px-16">
      <div class="mt-32 flex">
        <CarSidebar />
        <NuxtPage />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "car"
}
</script>

<style scoped>

</style>