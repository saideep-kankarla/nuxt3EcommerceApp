<template>
  <div>
    <nav>
      <NuxtLink to="/">Home </NuxtLink>
      <ul>
        <li><NuxtLink to="/">Home | </NuxtLink></li>
        <li><NuxtLink to="/about">About | </NuxtLink></li>
        <li><NuxtLink to="/products">Products</NuxtLink></li>
      </ul>
    </nav>
    <h2>Product = {{ id }}</h2>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Illum quidem
      veniam a nulla! Quibusdam dolorum blanditiis iusto? Veritatis, voluptas?
      Tempore doloribus illum non voluptatum repudiandae obcaecati impedit,
      ipsam sit at?
    </p>
  </div>
</template>

<script setup>
const { id } = useRoute().params;
</script>

<style scoped>
div {
  font-family: 'Courier New', Courier, monospace;
}
</style>
