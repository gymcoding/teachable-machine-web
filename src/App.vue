<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
      <v-toolbar-title>{{ title }}</v-toolbar-title>
    </v-app-bar>

    <v-main>
      <image-project></image-project>
    </v-main>
  </v-app>
</template>

<script>
import ImageProject from './components/ImageProject';

export default {
  name: 'App',

  components: {
    ImageProject
  },
  data: () => ({
    title: '짐코딩 칼로리'
  }),
};
</script>
