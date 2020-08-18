<template>
  <!-- App.vue -->

<v-app dark>
  <v-navigation-drawer>
    <!-- -->
  </v-navigation-drawer>

  <v-app-bar app>
    <!-- -->
    <v-spacer></v-spacer>
    <v-text-field
      class="ma-auto mt-1"
      label="Search"
      append-icon="fas fa-search"
      solo
      rounded
    ></v-text-field>
    <v-spacer></v-spacer>
  </v-app-bar>

  <!-- Sizes your content based upon application components -->
  <v-main>
    <!-- Provides the application the proper gutter -->
    <v-container>
      <router-view></router-view>
    </v-container>
  </v-main>

  <v-footer>
    <v-row class="text-center">
      <v-col>
        &copy; 2020 manisrinivasa
      </v-col>
    </v-row>
  </v-footer>
</v-app>
</template>

<script lang="ts">
import { dom } from '@fortawesome/fontawesome-svg-core';

export default {
  mounted() {
    dom.watch();
  },
  data() {
    return {

    };
  },
};
</script>

<style lang="scss" scoped>
</style>
