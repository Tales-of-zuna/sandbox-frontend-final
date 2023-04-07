<template>
  <v-sheet>
    <v-container grid-list-xs>
      <v-row class="d-flex justify-center"
        ><v-col cols="12" md="9">
          <v-row class="py-10"
            ><v-col cols="6" md="2" v-for="card in categories" :key="card"
              ><v-card hover class="py-10" color="red" dark
                ><div class="d-flex justify-center">
                  <v-icon x-large>{{ card.icon }}</v-icon>
                </div>
                <p
                  class="text-center white--text font-weight-bold text-subtitle-2 ma-0"
                >
                  {{ card.title }}
                </p></v-card
              ></v-col
            ></v-row
          >
        </v-col></v-row
      >
    </v-container></v-sheet
  >
</template>

<script>
export default {
  data() {
    return {
      categories: [
        {
          icon: "mdi-apple",
          title: "Apple",
        },
        {
          icon: "mdi-android",
          title: "Samsung",
        },
        {
          icon: "mdi-microsoft-xbox",
          title: "Xbox",
        },
        {
          icon: "mdi-sony-playstation",
          title: "Playstation ",
        },
        {
          icon: "mdi-microsoft",
          title: "Microsoft",
        },
        {
          icon: "mdi-nintendo-switch",
          title: "Nintendo",
        },
      ],
    };
  },
};
</script>

<style></style>
