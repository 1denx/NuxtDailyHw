<script setup>
const route = useRoute();
</script>

<template>
  <div>
    <h1>Page: index</h1>
    <p>目前路由的路徑 - route.fullPath為 :{{ route.fullPath }}</p>
    <button type="button" class="btn btn-primary">Primary</button>
    <button type="button" class="btn btn-secondary">Secondary</button>
    <button type="button" class="btn btn-success">Success</button>
    <button type="button" class="btn btn-danger">Danger</button>
    <button type="button" class="btn btn-warning">Warning</button>
    <button type="button" class="btn btn-info">Info</button>
    <button type="button" class="btn btn-light">Light</button>
    <button type="button" class="btn btn-dark">Dark</button>

    <button type="button" class="btn btn-link">Link</button>
  </div>
</template>

<style lang="scss">
$primary: blue;

h1 {
  color: $primary;
  font-size: $fs-xl;
}
</style>
