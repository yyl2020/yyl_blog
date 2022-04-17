<script setup lang="ts">
import Navbar from './components/Navigation/Navbar.vue';
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
</script>

<template>
  <div min-h-100vh overflow-hidden block relative pb-30 mx-auto flex flex-col>
    <Navbar />
    <main>
      <router-view />
    </main>
  </div>
</template>

<style>
body {
  margin: 0;
}
</style>
