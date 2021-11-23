<template>
   <main>
      <Content1/>
      <Content2/>
   </main>
</template>

<script>
import Content1 from './Content1.vue';
import Content2 from './Content2.vue';

export default {
   name: 'Main',
   components: {
      Content1,
      Content2
   }
}
</script>

<style scoped>
   main {
      height: calc(100vh - 80px - 80px - 100px);
      margin: 20px 0;
      display: flex;

      overflow-y: auto;
      /* border: 2px solid black; */
   }
</style>