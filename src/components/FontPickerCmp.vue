<template lang="html">
  <div class="">
    <font-picker :api-key="'AIzaSyANQn9ee4G8hUGsIPbeWPl0n6NHpji80q4'" :options="options" :active-font="fontFamily" @change="myFunc"></font-picker>
    <p class="apply-font" >Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>

  </div>
</template>

<script>
import FontPicker from 'font-picker-vue';
export default {
  name: "FontPickerCmp",
  components: {
    "font-picker": FontPicker,
  },
  data(){
   return {
     fontFamily: 'Abel',
   }
 },
 methods: {
  myFunc($event) {
    this.fontFamily = $event.family;
  }
}



}
</script>

<style lang="css" scoped>
</style>
