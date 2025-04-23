<template>
  <div class="text-3xl text-red-500 text-center">
    APP VUE
    <h1 class="text-3xl text-green-500 text-center mt-5 mb-5 ">
      
      SAlom hammaga
    </h1>
    <button-component></button-component>
  </div>
</template>
<script>
import ButtonComponent from './components/ButtonComponent.vue'
export default{
  components: {
    ButtonComponent
  }
}
</script>