<template>
  <article class="manga">
    <div class="thumbnail" :style="{ backgroundImage: 'url(' + tumbnail + ')' }"></div>
    <h1>{{ title }}</h1>
    <p>{{ previewText }}</p>
  </article>
</template>

<script>
  export default {
    props: ['thumbnail', 'title', 'previewText']
  }
</script>

<style scoped>

</style>