<template>
  <div>
    <header>
      <nav>
        <ul>
          <li><NuxtLink to="/">Home | </NuxtLink></li>
          <li><NuxtLink to="/about">About | </NuxtLink></li>
          <li><NuxtLink to="/products">Products</NuxtLink></li>
        </ul>
      </nav>
    </header>

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
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  p {
    color: black;
    font-style: italic;
  }
  ul {
    display: flex;
    margin: 0;
    padding: 0;

    li {
      list-style-type: none;
      flex-basis: content;
      margin-right: 10px;
      a {
        color: black;
      }
      .router-link-exact-active {
        color: rgb(24, 24, 141);
        font-weight: 800;
        text-decoration: underline;
      }
    }
  }
}
</style>
