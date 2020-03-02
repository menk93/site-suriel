<template>
  <v-app>
    <v-tooltip left>
      <template v-slot:activator="{ on }">
        <v-btn
          v-on="on"
          fixed
          color="#e38858"
          absolute
          top
          right
          fab
          style="margin-top: 40px"
          @click="redirecionar()"
        >
          <v-icon color="#9a7566">mdi-account</v-icon>
        </v-btn>
      </template>
      <span>Entrar</span>
    </v-tooltip>
    <nuxt />
    <v-footer :fixed="fixed" app>
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  data() {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          icon: "mdi-apps",
          title: "Welcome",
          to: "/"
        },
        {
          icon: "mdi-chart-bubble",
          title: "Inspire",
          to: "/inspire"
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: "Vuetify.js"
    };
  },
  methods: {
    redirecionar(){
      console.log("nada, nada");
      
    }
  }
};
</script>
