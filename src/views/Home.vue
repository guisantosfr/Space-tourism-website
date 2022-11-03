<script setup>
import Header from '../components/Header.vue';
</script>

<template>
  <Header />

  <div class="grid-container">
    <div>
      <h1 class="text-accent font-500 font-sans-cond uppercase letter-spacing-1">So, you want to travel to
        <span class="font-900 font-serif text-white">Space</span>
      </h1>

      <p>Let’s face it; if you want to go to space, you might as well genuinely go to
        outer space and not hover kind of on the edge of it. Well sit back, and relax
        because we’ll give you a truly out of this world experience!</p>
    </div>

    <router-link to="#" class="large-button uppercase font-serif font-600 text-dark bg-white">Explore</router-link>
  </div>
</template>