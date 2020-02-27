<template>
  <div>
    <v-card color="#1abc9c" class="ma-4">
      <v-card-actions>
        <v-list-item class="grow">
          <v-list-item-avatar>
            <v-img class="elevation-6" src="@/assets/project-icons/evolutionary-steering.svg"></v-img>
          </v-list-item-avatar>

          <v-list-item-content>
            <v-list-item-title class="headline font-weight-bold">Evolutionary Steering Behaviours</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-card-actions>
      <v-card-text class="headline font-weight-light subtitle-1">
        An Adaptation of Craig Reynolds research paper on Autonomous Agents. Created Autonomous steering agents which evolve the behavior of eating food (green dots) and avoiding poison (red dots).
        Implementation of Steering forces seek ,steer ,avoidance and an elementary Javascript based Physics Engine
      </v-card-text>
      <v-card-actions>
        <v-btn color="primary" dark @click.stop="evolutionarySteering = true">Open Project</v-btn>
        <v-btn
          class="ma-2"
          color="primary"
          dark
          href="https://editor.p5js.org/souravpd/sketches/qm8vVxQ-"
          target="_blank"
        >View Code</v-btn>
        <v-dialog v-model="evolutionarySteering" max-width="700" max-height="700">
          <v-card style="overflow:hidden;">
            <v-card-title class="headline">Evolutionary Steering Behaviours</v-card-title>
            <v-card-text center>
              <p>Drag Mouse To Insert More Agents</p>
              <iframe
                src="https://editor.p5js.org/souravpd/embed/qm8vVxQ-"
                width="660"
                height="360"
              ></iframe>
            </v-card-text>

            <v-card-actions>
              <v-spacer></v-spacer>
              <v-btn color="green darken-1" text @click="evolutionarySteering = false">Close</v-btn>
            </v-card-actions>
          </v-card>
        </v-dialog>
      </v-card-actions>
    </v-card>
    <v-card color="#ecf0f1" class="ma-4">
      <v-card-actions>
        <v-list-item class="grow">
          <v-list-item-avatar>
            <v-img class="elevation-6" src="@/assets/project-icons/ships.svg"></v-img>
          </v-list-item-avatar>
          <v-list-item-content>
            <v-list-item-title class="headline font-weight-bold">Ship Detection from Planet Imagery</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-card-actions>
      <v-card-text
        class="headline font-weight-light subtitle-1"
      >A combination of genetic algorithm with neural network. The difference between neuro-evolution of fixed topology (fixed number of hidden neurons) and NEAT is that the latter evolves not only the hidden weights but the connections and the number of neurons in a network as well</v-card-text>
      <v-card-actions>
        <v-btn
          class="ma-2"
          color="primary"
          dark
          href="https://github.com/souravp-d/ShipDetection"
          target="_blank"
        >View Code</v-btn>
      </v-card-actions>
    </v-card>
    <v-card color="#f1c40f" class="ma-4">
      <v-card-actions>
        <v-list-item class="grow">
          <v-list-item-avatar>
            <v-img class="elevation-6" src="@/assets/project-icons/angry-birds.svg"></v-img>
          </v-list-item-avatar>

          <v-list-item-content>
            <v-list-item-title class="headline font-weight-bold">NEAT Flappy Bird</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-card-actions>
      <v-card-text
        class="headline font-weight-light subtitle-1"
      >A combination of genetic algorithm with neural network. The difference between neuro-evolution of fixed topology (fixed number of hidden neurons) and NEAT is that the latter evolves not only the hidden weights but the connections and the number of neurons in a network as well</v-card-text>
      <v-card-actions>
        <v-btn color="primary" dark @click.stop="flappybird = true">Open Project</v-btn>
        <v-btn
          class="ma-2"
          color="primary"
          dark
          href="https://github.com/souravp-d/neat-flappy-bird"
          target="_blank"
        >View Code</v-btn>
        <v-dialog v-model="flappybird" max-width="1000" max-height="1000" style="overflow:hidden;">
          <v-card style="overflow:hidden;">
            <v-card-title class="headline">NEAT Flappy Bird</v-card-title>
            <v-card-text>
              <iframe
                src="https://souravp-d.github.io/neat-flappy-bird/"
                width="1000"
                height="1000"
              ></iframe>
            </v-card-text>

            <v-card-actions>
              <v-spacer></v-spacer>
              <v-btn color="green darken-1" text @click="flappybird = false">Close</v-btn>
            </v-card-actions>
          </v-card>
        </v-dialog>
      </v-card-actions>
    </v-card>
    <v-card color="#2c3e50" class="ma-4" dark>
      <v-card-actions>
        <v-list-item class="grow">
          <v-list-item-avatar>
            <v-img class="elevation-6" src="@/assets/project-icons/bus.svg"></v-img>
          </v-list-item-avatar>
          <v-list-item-content>
            <v-list-item-title class="headline font-weight-bold">Bosch Route Optimization Challenge</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-card-actions>
      <v-card-text
        class="headline font-weight-light subtitle-1"
      >Developed a dynamic genetic algorithm to generate efficient routes for the employees of a company to commute to their workplace considering efficient filling of company buses, Time Constraints and Minimum Operational Cost for the company</v-card-text>
      <v-card-actions>
        <v-btn
          class="ma-2"
          color="primary"
          dark
          href="https://github.com/souravpd/Routing"
          target="_blank"
        >View Code</v-btn>
      </v-card-actions>
    </v-card>
    <v-card color="#d35400" class="ma-4" dark>
      <v-card-actions>
        <v-list-item class="grow">
          <v-list-item-avatar>
            <v-img class="elevation-6" src="@/assets/project-icons/rays.svg"></v-img>
          </v-list-item-avatar>

          <v-list-item-content>
            <v-list-item-title class="headline font-weight-bold">Ray Casting</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-card-actions>
      <v-card-text
        class="headline font-weight-light subtitle-1"
      >Raycasting is a rendering technique to create a 3D perspective in a 2D map. In this project a basic ray casting technique has been explored</v-card-text>
      <v-card-actions>
        <v-btn color="primary" dark @click.stop="rays = true">Open Project</v-btn>
        <v-btn
          class="ma-2"
          color="primary"
          dark
          href="https://editor.p5js.org/souravpd/sketches/xBPYLDYQ"
          target="_blank"
        >View Code</v-btn>
        <v-dialog v-model="rays" max-width="450" max-height="450" style="overflow:hidden;">
          <v-card style="overflow:hidden;">
            <v-card-title class="headline">Ray Casting</v-card-title>
            <v-card-text>
              <iframe
                src="https://editor.p5js.org/souravpd/embed/xBPYLDYQ"
                width="450"
                height="450"
              ></iframe>
            </v-card-text>

            <v-card-actions>
              <v-spacer></v-spacer>
              <v-btn color="green darken-1" text @click="rays = false">Close</v-btn>
            </v-card-actions>
          </v-card>
        </v-dialog>
      </v-card-actions>
    </v-card>
  </div>
</template>

<script>
export default {
  name: "Projects",
  data() {
    return {
      flappybird: false,
      evolutionarySteering: false,
      rays: false
    };
  }
};
</script>

<style>
</style>