<template>
  <div>
    <h2>About</h2>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Doloribus deserunt sed officiis reiciendis commodi eaque
      atque autem? Sit repellat neque molestias rerum minima tenetur porro accusamus, quo voluptatibus eligendi ratione.
    </p>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Doloribus deserunt sed officiis reiciendis commodi eaque
      atque autem? Sit repellat neque molestias rerum minima tenetur porro accusamus, quo voluptatibus eligendi ratione.
    </p>
    <div>{{ data }}</div>
  </div>
</template>

<script setup>
const { data } = await useFetch('/api/currency/GBP')
</script>

<style scoped>
h2 {
  margin-bottom: 20px;
  font-size: 36px;
}

p {
  margin: 20px 0;
}
</style>