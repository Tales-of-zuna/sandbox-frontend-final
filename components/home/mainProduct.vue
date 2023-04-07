<template>
  <v-container grid-list-xs>
    <v-row
      ><v-col cols="12"
        ><v-hover class="zuna" v-slot="{ hover }"
          ><v-sheet rounded :elevation="hover ? 5 : 0"
            ><v-img
              contain
              class="rounded"
              src="https://i02.appmifile.com/794_operator_global/24/03/2023/9f30f09d63005c74a95380431f9d64b3.jpg?f=webp"
            ></v-img></v-sheet></v-hover></v-col
    ></v-row>
  </v-container>
</template>

<script>
export default {};
</script>

<style>
.zuna {
  transition: all 0.5s ease;
}
</style>
