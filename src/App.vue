<script setup>
import AvatarForm from './components/AvatarForm.vue'
import AvatarImage from './components/AvatarImage.vue'
</script>

<template>
  <main>
    <div>Avatar Maker App</div>
    <AvatarForm />
    <AvatarImage />
  </main>
</template>

<style scoped>
main {
  max-width: 65rem;
  margin: 2rem auto;
}
</style>
