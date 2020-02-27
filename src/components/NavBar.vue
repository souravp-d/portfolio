<template>
  <div>
    <v-app-bar color="#34495e" dense dark>
      <v-avatar size="36px" class="ma-2" style="font-family: 'Montserrat', ;">
        <img src="@/assets/logo.svg" alt="Sourav Prasad" />
      </v-avatar>

      <v-toolbar-title class="headline font-weight-bold">Sourav Prasad</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn
        icon
        href="https://docs.google.com/document/d/1W_ZkwnI7ZMQ-Ykb49p3YcnHPiZhlp2gj-1KrGWLK0qc/edit?usp=sharing"
        target="_"
      >
        <v-icon>mdi-file-document-box</v-icon>
      </v-btn>

      <v-btn icon href="https://www.facebook.com/souravpd27" target="_">
        <v-icon>mdi-facebook</v-icon>
      </v-btn>
      <v-btn icon href="https://linkedin.com/in/sourav-prasad-5232087b" target="_">
        <v-icon>mdi-linkedin</v-icon>
      </v-btn>
      <v-btn icon href="https://www.instagram.com/souravp._.d/" target="_">
        <v-icon>mdi-instagram</v-icon>
      </v-btn>
      <v-btn icon href="https://github.com/souravpd" target="_">
        <v-icon>mdi-git</v-icon>
      </v-btn>
      <v-btn icon href="mailto:souravpd007@gmail.com" target="_">
        <v-icon>mdi-email</v-icon>
      </v-btn>
    </v-app-bar>
  </div>
</template>

<script>
export default {
  name: "NavBar"
};
</script>

<style>
</style>