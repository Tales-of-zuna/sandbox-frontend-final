<template>
  <v-container class="">
    <v-row
      ><v-col cols="12" md="6"
        ><v-hover class="zuna" v-slot="{ hover }"
          ><v-sheet rounded :elevation="hover ? 5 : 0"
            ><v-img
              height="580"
              contain
              class="rounded"
              src="https://i02.appmifile.com/870_operator_global/24/03/2023/558eccdc33e7eaff8d3f6299bdc1d0ba.jpg?f=webp"
              ><v-row height=""
                ><v-col cols="12" class="d-flex justify-center"
                  ><v-card elevation="0" color="transparent">
                    <v-card-title primary-title> title </v-card-title>
                  </v-card></v-col
                ></v-row
              ></v-img
            ></v-sheet
          ></v-hover
        ></v-col
      ><v-col cols="12" md="6"
        ><v-hover class="zuna" v-slot="{ hover }"
          ><v-sheet rounded :elevation="hover ? 5 : 0"
            ><v-img
              contain
              height="580"
              class="rounded"
              src="https://i02.appmifile.com/186_operator_global/27/02/2023/75c0a6dc878285737b1f254f5d0673f4.jpg?f=webp"
            ></v-img></v-sheet></v-hover></v-col
    ></v-row>
  </v-container>
</template>

<script>
export default {};
</script>

<style></style>
