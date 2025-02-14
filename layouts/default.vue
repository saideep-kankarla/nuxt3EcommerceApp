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

    <div>
      <slot />
    </div>
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
      a {
        color: black;
      }
      .router-link-exact-active {
        color: rgb(24, 24, 141);
      }
    }
  }
}
</style>
