<template>
  <div id="app">
    <b-container class="bv-example-row mb-3">
      <b-row cols="1">
        <b-col><Navbar /></b-col>
        <b-col><router-view class="content" /></b-col>
      </b-row>
    </b-container>
  </div>
</template>
<script>
import Navbar from "./components/Navbar.vue";

export default {
  name: "App",
  components: { Navbar },
};
</script>

<style lang="scss">
</style>
