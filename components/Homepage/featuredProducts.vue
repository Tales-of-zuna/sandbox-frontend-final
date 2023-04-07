<template>
  <v-container grid-list-xs>
    <v-row class="d-flex justify-center">
      <v-col cols="12" md="9"
        ><p class="font-weight-bold">Онцлох бүтээгдэхүүн</p>
        <v-divider class="mb-5"></v-divider>
        <v-row class=""
          ><v-col cols="6" md="2" v-for="card in 6" :key="card"
            ><CardsGeneralCard /></v-col
        ></v-row> </v-col
    ></v-row>
  </v-container>
</template>

<script>
export default {};
</script>

<style></style>
