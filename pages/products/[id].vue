<template>
  <div>
    <p>Product details for {{ id }}</p>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium,
      explicabo in maxime alias doloribus veritatis magni aliquid obcaecati
      possimus sed!
    </p>
  </div>
</template>

<script setup>
const { id } = useRoute().params;
</script>

<style scoped></style>
