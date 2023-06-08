<template>
  <q-page class="flex flex-center">
    <img
      src="../assets/Women/1-front-1.jpg"
      style="width: 200px; height: 300px"
    />
    <img :src="Images" />
    <p>{{ Object.keys(fls)[0] }}</p>
  </q-page>
</template>

<script setup>
import { ref } from "vue";
import Images from "../assets/Women/1-front-1.jpg?w=40&h=30";

const fls = import.meta.glob("../assets/SKU/*/meta.txt");

var p = ref("discus");
</script>
