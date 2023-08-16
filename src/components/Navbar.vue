<template>
  <v-toolbar class="pa-2">
    <!--      <v-app-bar-nav-icon></v-app-bar-nav-icon>-->
    <v-toolbar-title class="font-weight-bold font-italic text-h5">Vue Test App.</v-toolbar-title>
    <v-tabs
        center-active
        class="justify-center mt-9"
    >
      <v-btn class="font-weight-bold text-h6">
        Home
        <v-icon
            size="large"
            icon="mdi-chevron-down"
        ></v-icon>
      </v-btn>

      <v-btn class="font-weight-bold text-h6">
        About
        <v-icon
            size="large"
            icon="mdi-chevron-down"
        ></v-icon>
      </v-btn>

      <v-btn class="font-weight-bold text-h6">
        Gallery
        <v-icon
            size="large"
            icon="mdi-chevron-down"
        ></v-icon>
      </v-btn>
      <v-btn class="font-weight-bold text-h6">
        Contact
        <v-icon
            size="large"
            icon="mdi-chevron-down"
        ></v-icon>
      </v-btn>
    </v-tabs>

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
</template>

 <script>
 export default {
   name:"Navbar"
 }
 </script>