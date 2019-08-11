<template>
  <div id="app">
    <div class="row">
      <div class="col-xs-12 col-sm-8 offset-sm-2 col-md-6 offset-md-3">
        <h1>Font Picker</h1>
        <font-picker-el></font-picker-el>
      </div>
    </div>
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
