<template>
  <div class="app">
    <NavComponent />
    <SearchComponent />
    <router-view />
    <FooterComponent />
  </div>
</template>
<script>
import NavComponent from './components/NavComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
import SearchComponent from './components/SearchComponent.vue';
export default{
  components: {
    NavComponent,
    FooterComponent,
    SearchComponent,
  }
}
</script>