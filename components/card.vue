<template>
  <div
    class="shadow-lg bg-gray-700 hover:scale-101 hover:shadow-xl hover:transform transition p-10 flex items-center rounded-2xl cursor-pointer justify-center"
  >
    <img :src="image" alt="" />
  </div>
</template>

<script>
export default {
    props: ['image']
};
</script>

<style scoped>
</style>