<template>
  <v-sheet color="grey lighten-4">
    <v-container grid-list-xs>
      <v-row class="d-flex justify-center"
        ><v-col cols="12" md="9">
          <v-row class="py-10"
            ><v-col cols="6" md="2" v-for="card in categories" :key="card"
              ><v-card hover class="py-10"
                ><div class="d-flex justify-center">
                  <v-icon x-large>{{ card.icon }}</v-icon>
                </div>
                <p
                  class="text-center font-weight-bold text-subtitle-2 ma-0 text--secondary"
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
          icon: "mdi-ghost",
          title: "Консол",
        },
        {
          icon: "mdi-cellphone",
          title: "Утас",
        },
        {
          icon: "mdi-laptop",
          title: "Зөөврийн компьютер",
        },
        {
          icon: "mdi-treasure-chest-outline",
          title: "Цэнэглэгч кард",
        },
        {
          icon: "mdi-headphones",
          title: "Дагалдах хэрэгсэл",
        },
        {
          icon: "mdi-watch",
          title: "Smart devices",
        },
      ],
    };
  },
};
</script>

<style></style>
