<template>
  <section>
    <v-parallax 
      src="../assets/sea1.jpg"
      height="400"
    >
      <v-layout
        row
      >
        <v-flex 
          xs12 
          sm6
          md4
          lg3
          ma-5
        >
          <v-card 
            class="ma-5"
            id="intro"
          >
            <v-card-title primary-title>Tabula Rasa</v-card-title>
            <v-card-text class="mt-3 mb-5 black--text">
              Tabula Rasa is een partij die oplossingsgericht te werk gaat voor plannen voor de lange termijn. Een nieuw begin is mogelijk, 
              door middel van constructieve en pragmatische probleemoplossingen. Met onze ideeën zetten wij ons in voor naar een waardige 
              toekomst voor mens en natuur.
            </v-card-text>
          </v-card>
        </v-flex>
      </v-layout>
    </v-parallax>
  </section>
</template>

<script>
export default {

}
</script>

<style>
#intro {
  background-color: rgba(255, 255, 255, 0.85);
}

#intro > .v-card__text {
  line-height: 185%;
}

#intro > .v-card__title {
  background-color: rgba(255, 255, 255);
}
</style>