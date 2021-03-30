<template>
<div class="flex p-1">
  <div class="flex-none w-44 relative">
    <img src="../assets/iqah1.jpeg" alt="" class="absolute inset-0 w-full h-full object-cover" />
  </div>
  <form class="flex-auto py-7 px-8">
    <div class="flex flex-wrap items-baseline">
      <h3 class="w-full flex-none text-3xl text-black mb-1.5">
        Nur Syafiqah binti Abdullah
      </h3>
      <div class="text-sm text-gray-500 ml-3">
        Hobbies: 
      </div>
    </div>
    <p class="text-sm text-red-500">
      Watching korean drama and reading
    </p>
  </form>
</div>

</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>
