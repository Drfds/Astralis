<template>
  <div class="main-area">
    <h1 class="welcome">Welcome to Astralis Dashboard</h1>
    <div v-if="error" class="error-message">
      {{ error }}
    </div>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Illo similique exercitationem dicta et rem eos recusandae id expedita ex, deserunt eaque provident aperiam alias. Optio corrupti molestiae neque culpa placeat.
    </p>
  </div>
</template>

<script setup>
</script>

<style scoped>
  .welcome {
  display: flex;
  justify-content: center;
  align-items: center;

  color: rgb(199, 199, 199);
  font-size: 3rem;
  font-family: "Exo 2", sans-serif;
  font-optical-sizing: auto;
  font-weight: 600;
  font-style: normal;
  }
  .main-area p {
  display: flex;
  justify-content: center;
  align-items: center;

  color: rgb(199, 199, 199);
  }
</style>
