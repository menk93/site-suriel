<template>
  <v-img id="imgFundo" :src="require('@/assets/bg-white.jpg')">
    <v-layout row wrap justify-center>
      <v-flex class="imgLogo pt-8">
        <v-img :src="require('@/assets/logo.png')"></v-img>
      </v-flex>
    </v-layout>
  </v-img>
  
</template>

<script>
export default {};
</script>

<style lang="scss">
.imgLogo{
  max-width: 50%;
  max-height: 30%;

}
</style>