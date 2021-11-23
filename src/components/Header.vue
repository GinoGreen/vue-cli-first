<template>
   <header>
      <h1>La mia prima app con Vue CLI</h1>
   </header>
</template>

<script>
export default {
   name: 'Header'
}
</script>

<style scoped>
   header {
      height: 80px;
      width: 100%;

      display: grid;
      place-items: center;
   }
   h1 {
      text-align: center;
   }
</style>