<template>
  <div class="home">
    <h2>Home Page</h2>
    <div class="button">
      <button @click="goToAbout">Go to About Page</button>
    </div>
  </div>
</template>

<script setup>
import router from "@/router";

function goToAbout() {
  router.push("/about");
}
</script>
