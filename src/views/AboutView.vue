<template>
  <div class="about">
    <h1>This is an about page</h1>
    <div class="button">
      <button @click="goToHomePage">Go to Home Page</button>
    </div>
  </div>
</template>

<script setup>
import router from "@/router";

function goToHomePage() {
  router.go(-1);
}
</script>
