<template>
  <section id="investor">
    <v-container fluid >

      <v-row alighn="center" justify="center">
        <v-col cols="10">
          <v-card >
            <nobreak>
            <img align="center" justify="left" height="150px" max-height="200px" src="~@/assets/img/BuffiVentures_headers_participate_sm.png" alt="participate header image"/>
              <!-- v-btn 
              rounded
                outlined
                alighn="center"
                justify="right"
                large
                dark
                href="https://docs.google.com/forms/d/e/1FAIpQLSf8D4HZzDHLZtQ79_RVJk6PhisBupXK3GiMeVLlQRT5XlGToA/viewform?usp=sf_link" 
                target="_blank"
                class="mt-5"
                absolute
                right
                color="pink"
              >
                Learn More
              </v-btn -->
            </nobreak>


            <v-row class="text-center">
       
              <!-- v-col class="col-6">
                <div class="flex-center">
                  <v-card-text>
                    <div class="flex-center" align="center" alighn="center">
         
                      <a href="https://ethden.page.link/apply" target="_blank">
                        <img align="bottom" max-height="250px" alt="Pitch Us" src="~@/assets/img/gwei.png"/>
                        <br/>Pitch Us
                        </a>

                    </div>
                   
                  </v-card-text>
                  <v-divider style="margin-right: -23px" vertical v-if="this.$vuetify.breakpoint.mdAndUp"></v-divider>
                </div>
                <v-divider class="mx-4" v-if="!this.$vuetify.breakpoint.smAndUp"></v-divider>
              </v-col --> 
              <v-col class="col-6">
                <div class="flex-center">
                  <v-card-text>
                    <div class="flex-center">
         
                      <a href="https://ethden.page.link/investBV" target="_blank">

                        <img src="~@/assets/img/KingBuffi.png" max-height="250px" />
                        <br/>
                        Invest in BV
                        </a>

                    </div>
                   
                  </v-card-text>
                  <v-divider style="margin-right: -23px" vertical v-if="this.$vuetify.breakpoint.mdAndUp"></v-divider>
                </div>
                <v-divider class="mx-4" v-if="!this.$vuetify.breakpoint.smAndUp"></v-divider>
              </v-col>
              <v-col class="col-6">
                <div class="flex-center">
                  <v-card-text>
                    <div class="flex-center">
         
                      <a href="https://ethden.page.link/bvaffiliate" target="_blank">
                        <img src="~@/assets/img/BuffiTank.png" alt="Invest or Sponsor" max-height="270px" />
                        <br/>Become an Affiliate Member
                        </a>

                    </div>
                   
                  </v-card-text>
                  <v-divider style="margin-right: -23px" vertical v-if="this.$vuetify.breakpoint.mdAndUp"></v-divider>
                </div>
                <v-divider class="mx-4" v-if="!this.$vuetify.breakpoint.smAndUp"></v-divider>
              </v-col>
              

              </v-row>
              </v-card>
        </v-col>
        </v-row>
    

    </v-container>
  </section>
</template>

<style scoped>
#investor {
  background-image: url("~@/assets/img/ETH_site_backgrounds_night_1440x515.png");
  background-attachment: fixed;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;

}

#investor .container,
#investor .row {
  height: 100%;
}

img {
        width: auto;
        height: auto;
      }

</style>