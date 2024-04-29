<script setup lang="ts"></script>

<template>
  <div
    id="topnav-component"
    class="sticky top-0 container h-24 flex justify-between place-items-center"
  >
    <div class="bg-blue-300">
      <img class="w-full h-28 bg-red-300" src="@/assets/logo/logo.jpg" />
    </div>
    <div id="links" class="flex gap-10">
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/about">About Us</RouterLink>
      <RouterLink to="/services">Services</RouterLink>
      <RouterLink to="/pricing">Pricing</RouterLink>
      <RouterLink to="/contact">Contact</RouterLink>
    </div>
  </div>
</template>

<style scoped>
nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}
</style>
