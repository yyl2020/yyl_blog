<script setup lang="ts">
</script>
<template>
  <nav
    z-10 text-elucidator-700 dark:text-dark-repulser-400 relative h-20 px-4
    role="navigation"
    aria-label="navbar"
  >
    <div max-w-screen-lg mx-auto h-full flex flex-row items-center space-x-4>
      <div logo flex-1>
        <router-link to="/">
          YeyuLin Blog
        </router-link>
      </div>
      <div>
        <router-link to="/articles">
          Articles
        </router-link>
        <router-link to="/about">
          About
        </router-link>
      </div>
    </div>
  </nav>
</template>