<template>
  <div class="background flex px-16 py-10">

    <div>
      <h2 style="color: #8B84BA">TABLE HEADING</h2>

      <v-card class="second-background">
        <v-card class="d-flex justify-space-between px-4 py-4">

          <div class="d-flex">
            <div class="pr-5">
              <v-btn prepend-inner-icon="mdi-filter"  outlined style="color: #8B84BA; height: 42px; width: 80px" text-color="red" class="text-capitalize" >
              <span >
                <v-icon style="color: #8B84BA">
                  mdi-filter
                </v-icon>
              </span>
                Filter
              </v-btn>
            </div>

            <div class="field">
              <v-text-field background-color="#F2F0F9" prepend-inner-icon="mdi-magnify" hide-details="auto" outlined dense color="grey" class="text-field" placeholder="Search Users By Name, Email Or Date">

              </v-text-field>
            </div>
          </div>

          <div class="pl-4">
            <v-btn outlined class="white--text" style="color: mediumpurple; background-color: mediumpurple">
              Pay Dues
            </v-btn>
          </div>

        </v-card>

        <v-divider style="color: #8B84BA"/>

        <v-card class="header-background ">

<!--          <div>-->
<!--            <h1 class="black&#45;&#45;text">fsbfsfbdbsfbsdsbd</h1>-->
<!--          </div>-->
          <v-row no-gutters>
            <v-col cols="1">
              <div class="pl-5">
                <v-checkbox
                    color="indigo"
                    hide-details
                ></v-checkbox>
              </div>
            </v-col>



            <v-col cols="3">
              <div class="pt-5 text-uppercase font-weight-medium" style="color: #8B84BA">
                Name
              </div>
            </v-col>

            <v-col cols="4">
              <div class="pt-5 text-uppercase font-weight-medium" style="color: #8B84BA">
                User Status
              </div>
            </v-col>

            <v-col cols="2">
              <div class="pt-5 text-uppercase font-weight-medium" style="color: #8B84BA">
                Payment Status
              </div>
            </v-col>

            <v-col cols="1.3">
              <div class="pt-5 text-uppercase font-weight-medium" style="color: #8B84BA">
                Amount
              </div>
            </v-col>

<!--            <v-col cols="">-->
              <div class="pt-5 d-flex justify-end pr-5" style="color: #8B84BA">
                <v-icon>
                  mdi-dots-vertical
                </v-icon>
              </div>
<!--            </v-col>-->
          </v-row>

        </v-card>

        <v-divider style="color: #8B84BA"/>

      </v-card>
    </div>
<!--    <v-row >-->

<!--    </v-row>-->
<!--    <v-row class="text-center">-->
<!--      <v-col cols="12">-->
<!--        <v-img-->
<!--          :src="require('../assets/logo.svg')"-->
<!--          class="my-3"-->
<!--          contain-->
<!--          height="200"-->
<!--        />-->
<!--      </v-col>-->

<!--      <v-col class="mb-4">-->
<!--        <h1 class="display-2 font-weight-bold mb-3">-->
<!--          Welcome to Vuetify-->
<!--        </h1>-->

<!--        <p class="subheading font-weight-regular">-->
<!--          For help and collaboration with other Vuetify developers,-->
<!--          <br>please join our online-->
<!--          <a-->
<!--            href="https://community.vuetifyjs.com"-->
<!--            target="_blank"-->
<!--          >Discord Community</a>-->
<!--        </p>-->
<!--      </v-col>-->

<!--      <v-col-->
<!--        class="mb-5"-->
<!--        cols="12"-->
<!--      >-->
<!--        <h2 class="headline font-weight-bold mb-3">-->
<!--          What's next?-->
<!--        </h2>-->

<!--        <v-row justify="center">-->
<!--          <a-->
<!--            v-for="(next, i) in whatsNext"-->
<!--            :key="i"-->
<!--            :href="next.href"-->
<!--            class="subheading mx-3"-->
<!--            target="_blank"-->
<!--          >-->
<!--            {{ next.text }}-->
<!--          </a>-->
<!--        </v-row>-->
<!--      </v-col>-->

<!--      <v-col-->
<!--        class="mb-5"-->
<!--        cols="12"-->
<!--      >-->
<!--        <h2 class="headline font-weight-bold mb-3">-->
<!--          Important Links-->
<!--        </h2>-->

<!--        <v-row justify="center">-->
<!--          <a-->
<!--            v-for="(link, i) in importantLinks"-->
<!--            :key="i"-->
<!--            :href="link.href"-->
<!--            class="subheading mx-3"-->
<!--            target="_blank"-->
<!--          >-->
<!--            {{ link.text }}-->
<!--          </a>-->
<!--        </v-row>-->
<!--      </v-col>-->

<!--      <v-col-->
<!--        class="mb-5"-->
<!--        cols="12"-->
<!--      >-->
<!--        <h2 class="headline font-weight-bold mb-3">-->
<!--          Ecosystem-->
<!--        </h2>-->

<!--        <v-row justify="center">-->
<!--          <a-->
<!--            v-for="(eco, i) in ecosystem"-->
<!--            :key="i"-->
<!--            :href="eco.href"-->
<!--            class="subheading mx-3"-->
<!--            target="_blank"-->
<!--          >-->
<!--            {{ eco.text }}-->
<!--          </a>-->
<!--        </v-row>-->
<!--      </v-col>-->
<!--    </v-row>-->
  </div>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({

    }),
  }
</script>

<style scoped lang="scss">
.background {
  background-color: #F2F0F9;
  height: 100vh;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
}

.second-background {
  height: 100vh;
  border-radius: 12px;
  color: #ffffff;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
}

.text-field {
  width: 600px;
  height: 39px;
}

.header-background {
  background-color: #F2F0F9;
  height: 7vh;
  //width: 1000px;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
  //z-index: 2;
}



</style>