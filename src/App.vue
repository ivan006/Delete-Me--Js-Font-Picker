<template>
  <div id="app">
    <font-picker-el></font-picker-el>
  </div>
</template>

<script>
import FontPickerCmp from './components/FontPickerCmp.vue'
export default {
  name: 'app',
  components: {
    "font-picker-el": FontPickerCmp
  }
}
</script>

<style>

</style>
