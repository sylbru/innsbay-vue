<template>
  <div class="Domain">
    <h2 class="Domain__name">{{ domain.name }}</h2>
    <p class="Domain__description">{{ domain.description }}</p>
  </div>
</template>

<style>
  .Domain {
    border: 1px solid black;
    padding: 1em;
    font-size: 2em;
    margin: 1em;
  }

  .Domain__name {
    font-size: 1.5em;
  }

  .Domain__description {
    font-style: italic;
  }
</style>

<script>
export default {
  props: {
    domain: Object
  }
}
</script>
