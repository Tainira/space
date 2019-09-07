<template>
  <div class="container">
    <SpaceMenu />
    <ContactUs />
    <template v-if="true">
      <h1>A Space Exploration Startup</h1>
      <p>Text</p>
    </template>
    <Register />
    <Explore>{{ 3 + 2}} <template slot="other">{{ 3 + 2 }}</template></Explore>
    <a href="https://cdn.dribbble.com/users/2530765/screenshots/6967953/attachments/1474198/custom___1.jpg">Example</a>
    <v-btn color="success">Success</v-btn>
  </div>
</template>

<script>
import SpaceMenu from '~/components/SpaceMenu'
import ContactUs from '~/components/ContactUs'
import Register from '~/components/Register'
import Explore from '~/components/Explore'

export default {
  layout: 'default',

  components: { SpaceMenu, ContactUs, Register, Explore },

  head: {
    title: 'Space project'
  }
}
</script>

<style scoped>
  .container {
  max-width: 80%;
  background-color: #25ae90;
  color: white;
  }

  h1 {
  text-align: center;
  }
</style>
