<template>
  <v-app>
    <v-card
    class="menu"
    flat
    tile
  >
    <v-toolbar dense >
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
      
      <v-btn-navigation v-model="bottomNav">        
        <v-layout>
          <v-flex xl3 lg3 md3 sm3 xs3  >
            <v-btn value="empresa">
              <span>Empresa</span>
              <!-- <v-icon>mdi-history</v-icon> -->
            </v-btn>
          </v-flex>
        </v-layout>
        
        

      </v-btn-navigation>

      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon>mdi-magnify</v-icon>
      </v-btn>

      <v-btn icon>
        <v-icon>mdi-heart</v-icon>
      </v-btn>

      <v-btn icon>
        <v-icon>mdi-dots-vertical</v-icon>
      </v-btn>
    </v-toolbar>
  </v-card>
    <nuxt />
    <description/>
    <!-- <v-footer :fixed="fixed" app>
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer> -->
  </v-app>
</template>

<script>
import description from "@/components/description"

export default {
  components: {
    description
  },

  data() {
    return {
      clipped: false,
      bottomNav: 'recent',
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
