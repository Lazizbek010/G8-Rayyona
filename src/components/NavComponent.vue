<template>
  <div class="nav">
      <div class="nav__top">
        <div class="container">
          <div class="logo"></div>
          <div class="links">
            <router-link to="/">Home</router-link>
            <router-link to="/properties">Properties</router-link>
            <router-link to="/contacts">Contacts</router-link>
          </div>
          <div class="login"></div>
        </div>
      </div>
      <div class="nav__bottom"></div>
  </div>
</template>

<script>
export default {
  setup () {
    

    return {}
  }
}
</script>

<style lang="scss" scoped>

</style>