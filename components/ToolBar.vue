<template>
  <v-content>
    <!-- toolbar 1 -->
    <v-toolbar dark :color="primary">
      <v-toolbar-side-icon></v-toolbar-side-icon>
      <v-toolbar-title>{{primary}}</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items class="hidden-sm-and-down">
        <v-btn flat>Link One</v-btn>
        <v-btn flat>Link Two</v-btn>
        <v-btn flat>Link Three</v-btn>
      </v-toolbar-items>
    </v-toolbar>

    <!-- toolbar 2 -->
    <v-toolbar dark :color="secundary">
      <v-toolbar-side-icon></v-toolbar-side-icon>

      <v-toolbar-title class="white--text">{{secundary}}</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon>search</v-icon>
      </v-btn>

      <v-btn icon>
        <v-icon>apps</v-icon>
      </v-btn>

      <v-btn icon>
        <v-icon>refresh</v-icon>
      </v-btn>

      <v-btn icon>
        <v-icon>more_vert</v-icon>
      </v-btn>
    </v-toolbar>

    
 
  
  </v-content>
</template>

<script>
  export default {
    data: () => ({
      primary: 'blue darken-2',
      secundary: 'orange darken-3'
    })
  }
</script>