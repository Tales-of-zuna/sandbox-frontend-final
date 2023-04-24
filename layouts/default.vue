<template>
  <v-app>
    <v-app-bar color="white" app elevate-on-scroll
      ><v-app-bar-nav-icon class="d-flex d-md-none"></v-app-bar-nav-icon
      ><v-container grid-list-xs>
        <v-row class="d-flex justify-center"
          ><v-col cols="10" class="align-center d-flex"
            ><img
              width="100"
              src="https://img-prod-cms-rt-microsoft-com.akamaized.net/cms/api/am/imageFileData/RW4ESm?ver=c63e"
              alt=""
            />
            <v-menu
              open-on-hover
              bottom
              transition="slide-y-transition"
              offset-y
            >
              <template v-slot:activator="{ on, attrs }">
                <v-btn
                  v-bind="attrs"
                  v-on="on"
                  text
                  color="grey darken-3 "
                  class="text--text text-capitalize ml-5"
                  >Утас</v-btn
                >
              </template>
              <v-sheet color="white" class="flex pa-10 justify-center"
                ><v-row class="d-flex justify-center"
                  ><v-col cols="9" class="d-flex justify-center"
                    ><v-card
                      v-for="hola in 6"
                      :key="hola"
                      hover
                      class="mx-4 px-15 py-10"
                      ><div class="d-flex justify-center">
                        <v-icon x-large>mdi-ghost</v-icon>
                      </div>
                      <p
                        class="text-center font-weight-bold text-subtitle-2 ma-0 text--secondary"
                      >
                        Apple
                      </p></v-card
                    ></v-col
                  ></v-row
                ></v-sheet
              >
            </v-menu>
            <v-btn
              text
              color="grey darken-3"
              class="text--text text-capitalize ml-5"
              >Консол</v-btn
            ><v-btn
              text
              color="grey darken-3"
              class="text--text text-capitalize ml-5"
              >Зөөврийн компьютер</v-btn
            >
            <v-spacer> </v-spacer>
            <v-btn
              text
              color="grey darken-3"
              class="text--text text-capitalize ml-5"
              >хямдралтай</v-btn
            ><v-btn
              text
              color="grey darken-3"
              class="text--text text-capitalize ml-5"
              >Тусламж</v-btn
            >
            <v-btn
              icon
              color="grey darken-3"
              class="text--text text-capitalize ml-5"
              ><v-icon>mdi-magnify</v-icon></v-btn
            ><v-btn
              icon
              color="grey darken-3"
              class="text--text text-capitalize ml-5"
              ><v-icon>mdi-account</v-icon></v-btn
            >
            <v-btn
              icon
              color="grey darken-3"
              class="text--text text-capitalize ml-5"
              ><v-icon>mdi-cart</v-icon></v-btn
            >
          </v-col></v-row
        >
      </v-container></v-app-bar
    >
    <v-main>
      <Nuxt />
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: "DefaultLayout",
  data() {
    return {};
  },
};
</script>
