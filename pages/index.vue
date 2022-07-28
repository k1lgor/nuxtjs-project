<template >
  <div id="container">
    <h1>Planets</h1>
    <h1>Planets</h1>
    <h1>Planets</h1>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark mt-5 rounded">
      <nuxt-link
        type="button"
        class="btn btn-outline-light m-sm-auto"
        to="/mercury"
      >
        Mercury
      </nuxt-link>
      <nuxt-link
        type="button"
        class="btn btn-outline-light m-sm-auto"
        to="/venus"
      >
        Venus
      </nuxt-link>
      <nuxt-link
        type="button"
        class="btn btn-outline-light m-sm-auto"
        to="/earth"
      >
        Earth
      </nuxt-link>
      <nuxt-link
        type="button"
        class="btn btn-outline-light m-sm-auto"
        to="/mars"
      >
        Mars
      </nuxt-link>
      <nuxt-link
        type="button"
        class="btn btn-outline-light m-sm-auto"
        to="/jupiter"
        >Jupiter</nuxt-link
      >
      <nuxt-link
        type="button"
        class="btn btn-outline-light m-sm-auto"
        to="/saturn"
      >
        Saturn
      </nuxt-link>
      <nuxt-link
        type="button"
        class="btn btn-outline-light m-sm-auto"
        to="/uranus"
      >
        Uranus
      </nuxt-link>
      <nuxt-link
        type="button"
        class="btn btn-outline-light m-sm-auto"
        to="/neptune"
      >
        Neptune
      </nuxt-link>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>

<style>
@import '../assets/style.css';
</style>