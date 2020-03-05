<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
      dense
    >
      <v-btn text icon>
        <v-icon>mdi-bell</v-icon>
      </v-btn>
      <v-btn v-show="false" text icon>
        <v-icon>mdi-keyboard-backspace</v-icon>
      </v-btn>

      <v-spacer></v-spacer>

      <v-btn text icon>
        <v-icon>mdi-exit-to-app</v-icon>
      </v-btn>
    </v-app-bar>

    <v-content>
      <HelloWorld/>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
