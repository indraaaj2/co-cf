<template>
  <q-page class="flex flex-center">
    <img :src="Images" />
    <p>{{ Object.keys(fls)[0] }}</p>
  </q-page>
</template>

<script setup>
import { ref } from "vue";
import Images from "../assets/Women/1-front.jpg?w=100";

const fls = import.meta.glob("../assets/SKU/*/meta.txt");

var p = ref("discus");
</script>
