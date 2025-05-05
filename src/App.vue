<template>
  <div class="app">
    <NavComponent />
    <router-view />
    <FooterComponent />
  </div>
</template>
<script>
import NavComponent from './components/NavComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
export default{
  components: {
    NavComponent,
    FooterComponent,
  }
}
</script>