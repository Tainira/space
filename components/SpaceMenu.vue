<template>
  <div class="menu">
    <ul>
      <li class="menu__elements menu__active">Home</li>
      <li class="menu__elements">About</li>
      <li class="menu__elements">Service</li>
      <li class="menu__elements">Explore</li>
    </ul>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.menu {
  color: white;
  display: inline;
}

.menu__elements {
  display: inline;
}

.menu__active {
  font-weight: bold;
}
</style>
