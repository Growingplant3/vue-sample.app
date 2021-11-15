<template>
  <v-app>
    <bot-navbar></bot-navbar>
    <v-app-bar>
      <main-content></main-content>
    </v-app-bar>
  </v-app>
</template>

<script>
import mainContent from './components/mainContent';
import botNavbar from './components/botNavbar.vue';

export default {
  name: 'App',

  components: {
    mainContent,
    botNavbar,
  },

  data: () => ({
    //
  }),
};
</script>
