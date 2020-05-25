<template>
  <v-img id="imgFundo" :src="require('@/assets/background-doce.jpeg')">
  <!-- <v-parallax id="imgFundo" :src="require('@/assets/background-doce.jpeg')"> -->
    <v-layout row wrap justify-center>
      <v-flex class="imgLogo">
        <v-img :src="require('@/assets/logo.png')"></v-img>
      </v-flex>
    </v-layout>
  <!-- </v-parallax> -->
  </v-img>
  
</template>

<script>
export default {

  mounted() {
    document.getElementById("imgFundo").style.height = "100vh";
  },
};
</script>

<style lang="scss">
.imgLogo{
  padding-top: 13vh;
  margin-right: 70vh;
  max-width: 100vh;
}
#imgFundo {
  position: relative;
  height: 100%;
}
</style>