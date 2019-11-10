<template>
  <div>
    <section>
      <v-parallax src="../assets/data-center.jpg" height="600" dark>
        <v-row align="center" justify="center">
          <v-col class="text-center" cols="12">
            <h1 class="display-2 mb-4">We are LAN Scapers</h1>
            <h4 class="display-1">Empowering local businesses with enterprise IT services.</h4>
          </v-col>
        </v-row>
      </v-parallax>
    </section>
    <section>
      <v-row align="center" justify="center">
        <v-container grid-list-xl>
          <v-layout row wrap align-center>
            <v-flex xs12 md4>
              <v-card flat class="grey--darken-2">
                <v-card-text class="text-center">
                  <v-icon x-large class="blue--text text--lighten-2">mdi-business</v-icon>
                </v-card-text>
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline text-center">Customers First</div>
                </v-card-title>
                <v-card-text>At Lanscapers, we care about our local business customers. We want to empower our community with IT solutions that help them run their business in an interconnected world. We're here to bring our community together with our networking solutions.</v-card-text>
              </v-card>
            </v-flex>
            <v-flex xs12 md4>
              <v-card flat class="grey--darken-2">
                <v-card-text class="text-center">
                  <v-icon x-large class="blue--text text--lighten-2">mdi-flash</v-icon>
                </v-card-text>
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline">Fast development</div>
                </v-card-title>
                <v-card-text>
                  Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare.
                  Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
                  Nullam in aliquet odio. Aliquam eu est vitae tellus bibendum tincidunt. Suspendisse potenti.
                </v-card-text>
              </v-card>
            </v-flex>
            <v-flex xs12 md4>
              <v-card flat class="grey--darken-2">
                <v-card-text class="text-center">
                  <v-icon x-large class="blue--text text--lighten-2">mdi-wrench</v-icon>
                </v-card-text>
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline text-center">Completely Open Sourced</div>
                </v-card-title>
                <v-card-text>
                  Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare.
                  Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
                  Nullam in aliquet odio. Aliquam eu est vitae tellus bibendum tincidunt. Suspendisse potenti.
                </v-card-text>
              </v-card>
            </v-flex>
          </v-layout>
        </v-container>
      </v-row>
    </section>
    <section>
      <v-parallax src="../assets/datacenter.jpg" height="600">
        <v-row align="center" justify="center">
          <v-col class="text-center" cols="12">
            <h1 class="display-1 mb-4">LANScapers</h1>
            <h4 class="subheading">Local IT supporting small businesses in Jacksonville, Florida</h4>
          </v-col>
        </v-row>
      </v-parallax>
    </section>
    <section>
      <v-container grid-list-xl>
        <v-layout row wrap justify-center class="my-12">
          <v-flex xs12 sm4>
            <v-card flat class="transparent">
              <v-card-title primary-title class="layout justify-center">
                <div class="headline">About Us</div>
              </v-card-title>
              <v-card-text>The Lanscapers is a small family owned business of IT professionals. At Lanscapers, we do our best to empower small local businesses with resilient IT setups for everything from cashiering solutions like Square Reader to routers for WiFi.</v-card-text>
            </v-card>
          </v-flex>
          <v-flex xs12 sm4 offset-sm1>
            <v-card flat class="transparent">
              <v-card-title primary-title class="layout justify-center">
                <div class="headline">Contact us today</div>
              </v-card-title>
              <v-card-text>We're here for your all of your IT business setup needs! Contact us by phone or email and we'll get back to you as soon as possible.</v-card-text>
              <v-list class="transparent">
                <v-list-item>
                  <v-list-item-action>
                    <v-icon class="blue--text text--lighten-2">mdi-phone</v-icon>
                  </v-list-item-action>
                  <v-list-item-content>
                    <v-list-item-title>303-570-3625</v-list-item-title>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item>
                  <v-list-item-action>
                    <v-icon class="blue--text text--lighten-2">mdi-map-marker</v-icon>
                  </v-list-item-action>
                  <v-list-item-content>
                    <v-list-item-title>Rapid City, South Dakota</v-list-item-title>
                  </v-list-item-content>
                </v-list-item>
                <v-list-item>
                  <v-list-item-action>
                    <v-icon class="blue--text text--lighten-2">mdi-email</v-icon>
                  </v-list-item-action>
                  <v-list-item-content>
                    <v-list-item-title>kylearnoldmiller@gmail.com</v-list-item-title>
                  </v-list-item-content>
                </v-list-item>
              </v-list>
            </v-card>
          </v-flex>
        </v-layout>
      </v-container>
    </section>

    <v-footer color="blue darken-2">
      <v-layout row wrap align-center>
        <v-flex xs12>
          <div class="white--text ml-4">The Lanscapers LLC</div>
        </v-flex>
      </v-layout>
    </v-footer>
  </div>
</template>

<script>
export default {
  data: () => ({})
};
</script>
