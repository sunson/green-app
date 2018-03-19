<template>
  <div>
    <img src="@/assets/logo.png" class="GREENLogoBig" v-if="(size==='big')">
    <img src="@/assets/logo.png" class="GREENLogoMedium" v-if="(size==='medium')">
    <img src="@/assets/logo.png" class="GREENLogoSmall" v-if="(size==='small')">
  </div>
</template>

<script>
  export default {
  props: ['size']
  }
</script>

<style>
  .GREENLogoBig {
  width: 200px;
  height: 200px;
  }
  .GREENLogoMedium {
  width: 110px;
  height: 110px;
  }
  .GREENLogoSmall {
  width: 65px;
  height: 65px;
  }
</style>
