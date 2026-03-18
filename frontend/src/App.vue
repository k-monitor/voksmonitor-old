<template>
  <div class="archive-banner">
    Most a Voksmonitor archívumát nézed.
    <a href="https://voksmonitor.hu/" class="archive-banner-link">
      Kattints ide a legfrissebb Voksmonitorért! ↗
    </a>
  </div>
  <Suspense>
    <router-view />
  </Suspense>
</template>

<style scoped>
.archive-banner {
  background-color: rgb(12, 124, 89);
  color: rgb(255, 255, 255);
  text-align: center;
  padding: 0.625rem 1rem;
  font-family: 'Inter', sans-serif;
  font-size: 0.875rem;
  font-weight: 400;
  letter-spacing: 0.01em;
}

.archive-banner-link {
  color: rgb(255, 255, 255);
  font-weight: 700;
  text-decoration: underline;
  text-underline-offset: 2px;
}

.archive-banner-link:hover {
  color: rgb(165, 238, 217);
}
</style>
