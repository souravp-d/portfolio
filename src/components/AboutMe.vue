<template>
  <v-card class="mx-auto" color="#3498db" dark>
    <v-card-title>
      <v-list-item-avatar>
        <v-img class="elevation-6" src="@/assets/about-me.svg"></v-img>
      </v-list-item-avatar>
      <span class="title font-weight-light">About Me</span>
    </v-card-title>

    <v-card-text
      class="headline font-weight-bold"
    >"I’m not the best student a teacher can get. I lie low, quiet, barely raise my hand. I’m forgetful and lazy, often procrastinating on assignments completing them in the end hours… But I’ve managed to maintain a good impression in front of all my teachers. The reason being, I’m dedicated, if I turn in an assignment late, I’d go above and beyond and work my absolute hardest. I’m quiet, but I try and pay attention in class and try my best to outperform myself everyday."</v-card-text>

    <v-card-actions>
      <v-list-item class="grow">
        <v-list-item-avatar tile>
          <v-img class="elevation-6" src="@/assets/avatar.svg"></v-img>
        </v-list-item-avatar>

        <v-list-item-content>
          <v-list-item-title>Sourav Prasad</v-list-item-title>
          <v-list-item-title>Bachelor of Technology Mineral Engineering</v-list-item-title>
          <v-list-item-title>Indian Institute of Technology (Indian School of Mines) Dhanbad</v-list-item-title>
          <v-list-item-title>CGPA : 9.17 (Current)</v-list-item-title>
        </v-list-item-content>
      </v-list-item>
    </v-card-actions>
  </v-card>
</template>

<script>
export default {
  name: "AboutMe"
};
</script>

<style>
</style>