<template>
  <div class="home">
    <v-container>
      <v-row no-gutters>
        <v-col cols="8">
          <AboutMe class="ma-4" />
        </v-col>
        <v-col cols="4">
          <Sidebar />
        </v-col>
      </v-row>
      <v-divider :inset="inset" light></v-divider>
      <v-subheader class="headline font-weight-bold">Projects</v-subheader>
      <v-row no-gutters>
        <v-col cols="8">
          <Projects />
        </v-col>
        <v-col cols="4"></v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
// @ is an alias to /src
import AboutMe from "@/components/AboutMe.vue";
import Sidebar from "@/components/Sidebar.vue";
import Projects from "@/components/Projects.vue";
export default {
  name: "Home",
  components: {
    AboutMe,
    Sidebar,
    Projects
  }
};
</script>
