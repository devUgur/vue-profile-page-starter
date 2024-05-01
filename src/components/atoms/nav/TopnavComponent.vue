<script setup lang="ts"></script>

<template>
  <nav id="topnav-component" class="sticky top-0 h-24 z-20 bg-gray-800 text-white">
    <div class="container flex justify-between items-center">
      <div>
        <img class="w-auto h-16 sm:h-24" src="@/assets/logo/logo.jpg" alt="Logo" />
      </div>
      <div id="links" class="gap-4 sm:gap-10 hidden sm:flex">
        <RouterLink to="/" class="nav-link">Home</RouterLink>
        <RouterLink to="/about" class="nav-link">About Us</RouterLink>
        <RouterLink to="/services" class="nav-link">Services</RouterLink>
        <RouterLink to="/portfolio" class="nav-link">Portfolio</RouterLink>
        <RouterLink to="/pricing" class="nav-link">Pricing</RouterLink>
        <RouterLink to="/contact" class="nav-link">Contact</RouterLink>
      </div>
    </div>
  </nav>
</template>

<style scoped>
nav {
  width: 100%;
}

.nav-link {
  padding: 0.5rem 1rem;
  border-left: 1px solid var(--color-border);
}

.nav-link:first-of-type {
  border: 0;
}
</style>
