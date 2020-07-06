<template>
  <div id='header'>
    <h1 class="title"> {{title}} </h1>
  </div>
</template>

<script>
export default {
  
  data() {
    return {
      title: 'MineSweeper'
    }
  }
    
}

</script>


<style scoped>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  h1 {
    color: red;
    font-size: 32px;
  }

</style>
