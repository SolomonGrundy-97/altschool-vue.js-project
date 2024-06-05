<script setup>
  import githubIcon from './icons/githubIcon.vue';
</script>

<template>

  <nav>
    <div class="navbar">
      <githubIcon class="github-icon"/>
      <h1>UZOMA SOLOMON GITHUB REPOS.</h1>
    </div>
  </nav>

</template>

<style scoped>

.navbar {
  display: flex;
  align-items: center;
  gap: 10px;
  justify-content: center;
  background-color: #1B9AAA;
  text-align: center;
  padding: 20px;
  margin-bottom: 100px
}

.github-icon {
  font-size: 7rem;
}
</style>
