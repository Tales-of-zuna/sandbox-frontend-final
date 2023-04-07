<template>
  <v-sheet color="grey lighten-4">
    <v-container grid-list-xs>
      <v-row class="d-flex justify-center"
        ><v-col cols="12" md="9">
          <v-row class="py-10"
            ><v-col cols="12" md="4"
              ><p class="font-weight-bold pt-6">Онцгой хямдрал</p>
              <v-img
                class="d-flex align-center"
                src="https://d-themes.com/vue/porto/demo-21/images/home/banners/banner-3.jpg"
                ><v-card elevation="0" color="transparent" width="200">
                  <v-card-title primary-title class="text-h5 font-weight-bold">
                    Elec Deals
                  </v-card-title>
                  <v-card-subtitle class="text-h6 d-flex align-end">
                    <p class="font-weight-bold">$59.00</p>
                    <p
                      class="text--disabled mx-2 font-weight-bold text-decoration-line-through text-subtitle-1"
                    >
                      $59.00
                    </p></v-card-subtitle
                  ><v-card-actions class="mt-n5">
                    <v-btn color="red" dark class="ml-2">text</v-btn>
                  </v-card-actions>
                </v-card></v-img
              ></v-col
            ><v-col cols="12" md="8"
              ><v-tabs
                background-color="transparent"
                color="grey darken-2"
                slider-color="grey"
              >
                <v-tab ripple> Утас </v-tab>
                <v-tab ripple> Зөөврийн компьютер </v-tab>
                <v-tab ripple> Console </v-tab>
                <v-tab-item>
                  <v-row class="pt-4"
                    ><v-col v-for="item in 4" :key="item" cols="6" md="3"
                      ><CardsGeneralCard /></v-col></v-row></v-tab-item
                ><v-tab-item>
                  <v-row class="pt-4"
                    ><v-col v-for="item in 4" :key="item" cols="6" md="3"
                      ><CardsGeneralCard /></v-col
                  ></v-row> </v-tab-item
                ><v-tab-item>
                  <v-row class="pt-4"
                    ><v-col v-for="item in 4" :key="item" cols="6" md="3"
                      ><CardsGeneralCard /></v-col
                  ></v-row>
                </v-tab-item> </v-tabs></v-col
          ></v-row> </v-col
      ></v-row> </v-container
  ></v-sheet>
</template>

<script>
export default {
  data() {
    return {};
  },
};
</script>

<style></style>
