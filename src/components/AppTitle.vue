<script>
export default {
  data() {
    return { 
      message: 'La mia prima volta con Vue'
    }
  }
}
</script>

<template>
  <header>
    <h1>
      {{ message }}
    </h1>
  </header>
</template>

<style scoped>
header {
  background-color: aquamarine;
  text-align: center;
  padding: 20px 0;
}

h1 {
  color: lightcoral;
  font-size: 2rem;
}
</style>