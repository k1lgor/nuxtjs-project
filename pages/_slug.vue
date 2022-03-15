<template>
  <div id="container">
    <h1>{{ planet.title }}</h1>
    <h1>{{ planet.title }}</h1>
    <h1>{{ planet.title }}</h1>
    <img :src="planet.image" alt="" width="200" height="200" class="rounded" />
    <div>
      <p>Description: {{ planet.description }}</p>
      <p v-if="planet.radius">Radius: {{ planet.radius }}</p>
      <p v-if="planet.distanceFromSun">
        Distance from the Sun: {{ planet.distanceFromSun }}
      </p>
    </div>
    <nuxt-link type="button" class="btn btn-outline-light" to="/">
      Planets
    </nuxt-link>
  </div>
</template>

<script>
export default {
  async asyncData({ params }) {
    const planet = await fetch(
      `https:/api.nuxtjs.dev/planets/${params.slug}`
    ).then((res) => res.json())
    return { planet }
  },
}
</script>

<style>
@import '../assets/style.css';
</style>