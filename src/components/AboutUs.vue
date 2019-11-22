<template>
  <section>
    <v-layout
      column
      wrap
      align-center
      class="full"
    >
      <v-flex 
        xs10
        class="bg"
      >
        <v-container grid-list-xl>
          <h1 class="mb-1">OVER ONS.</h1>
          <v-divider class="mb-3"></v-divider>
          <v-layout 
            row 
            wrap 
            align-center
          >
            <v-flex 
              xs12
              md6
            >
              <v-card href="#">
                <v-img 
                  src="../assets/manifest-themes/climate1.jpg"
                  height="200"
                  gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
                  class="align-end"
                >
                  <v-card-title primary-title class="white--text pa-5 pl-10">Standpunten</v-card-title>
                </v-img>
              </v-card>
            </v-flex>
            <v-flex 
              xs12
              md6
            >
              <v-card 
                href="/manifest-tabula_rasa.pdf" 
                download
              >
                <v-img 
                  src="../assets/manifest-themes/people1.jpg"
                  height="200"
                  gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
                  class="align-end"
                >
                  <v-card-title primary-title class="white--text pa-5 pl-10">Manifest</v-card-title>
                </v-img>
              </v-card>
            </v-flex>
          </v-layout>
        </v-container>
      </v-flex>
    </v-layout>
  </section>
</template>

<script>
export default {

}
</script>

<style>
</style>