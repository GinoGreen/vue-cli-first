<template>
   <section id="content2">
      <Content3/>
      <Content4/>
   </section>
</template>

<script>
import Content3 from './Content3.vue'
import Content4 from './Content4.vue'

export default {
   name: 'Content2',
   components: {
      Content3,
      Content4
   }
}
</script>

<style scoped>
   #content2 {
      height: 100%;
      width: calc(40% - 20px);

      margin-left: 20px;
   }
</style>