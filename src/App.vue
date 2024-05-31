<template>
  <v-app>
    <v-main>
      <HeaderLayout />
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
import HeaderLayout from "./components/layout/HeaderLayout.vue";

export default {
  name: "App",

  data: () => ({
    //
  }),

  components: {
    HeaderLayout,
  },
};
</script>
