<template>
  <div>
    <b-nav class="mynav">
      <b-nav-item disabled><strong>Fancy Quiz App</strong></b-nav-item>
      <b-nav-item disabled>Counter: {{ numCorrect }}/{{ numTotal }}</b-nav-item>      
    </b-nav>
  </div>
</template>

<script>
export default {
  name: 'Header',
  props: [
    'numCorrect',
    'numTotal'
  ]
  
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .mynav {
    height: 50px;
    align-items: center;
  }
</style>
