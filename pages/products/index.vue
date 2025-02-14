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

    <h2>Products Catalog</h2>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Illum quidem
      veniam a nulla! Quibusdam dolorum blanditiis iusto? Veritatis, voluptas?
      Tempore doloribus illum non voluptatum repudiandae obcaecati impedit,
      ipsam sit at?
    </p>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Illum quidem
      veniam a nulla! Quibusdam dolorum blanditiis iusto? Veritatis, voluptas?
      Tempore doloribus illum non voluptatum repudiandae obcaecati impedit,
      ipsam sit at?
    </p>
  </div>
</template>

<script setup></script>

<style scoped>
div {
  font-family: 'Courier New', Courier, monospace;
  ul {
    display: flex;
    margin: 0;
    padding: 0;

    li {
      list-style-type: none;
      flex-basis: content;
      margin-right: 10px;
    }
  }
}
</style>
