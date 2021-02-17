<template>
  <div class="container mx-auto">
    <div class="w-full mt-72">
      <Logo />
      <h1 class="title text-center">
        tailwind-projects
      </h1>
      <div class="gap-2 grid grid-cols-3 mt-64 mb-64"> <!-- componentize -->
        <card image="~/assets/youtube.png"></card>
        <div class="shadow-lg bg-gray-700 hover:scale-101 hover:shadow-xl hover:transform transition p-10 flex items-center rounded-2xl cursor-pointer justify-center"><img src="~/assets/youtube.png" alt=""></div>
        <nuxt-link to="github">
          <div class="shadow-lg bg-gray-700 hover:scale-101 hover:shadow-xl hover:transform transition p-10 flex items-center rounded-2xl cursor-pointer justify-center"><img src="~/assets/github.png" alt=""></div>
        </nuxt-link>
        <div class="shadow-lg bg-gray-700 hover:scale-101 hover:shadow-xl hover:transform transition flex items-center justify-center cursor-pointer p-10 py-16 rounded-2xl"><img class="h-14" src="~/assets/twitter.png" alt=""></div>
        <div class="shadow-lg bg-gray-700 hover:scale-101 hover:shadow-xl hover:transform transition p-10 flex items-center rounded-2xl cursor-pointer justify-center py-14"><img class="h-48" src="~/assets/disney.png" alt=""></div>
        <div class="shadow-lg bg-gray-700 hover:scale-101 hover:shadow-xl hover:transform transition p-10 flex items-center rounded-2xl cursor-pointer"></div>
        <div class="shadow-lg bg-gray-700 hover:scale-101 hover:shadow-xl hover:transform transition flex items-center justify-center cursor-pointer p-10 py-16 rounded-2xl"></div>
      </div>
    </div>

  </div>
</template>

<script>
import Card from '../components/card.vue'
export default {}
</script>

<style>
Card
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
