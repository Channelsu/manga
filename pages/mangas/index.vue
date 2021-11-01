<template>
  <section class="mangas">
    <article class="manga">
      <div></div>
      <h1>マンガ名</h1>
      <p>説明文</p>
    </article>
    <article class="manga">
      <div></div>
      <h1>マンガ名</h1>
      <p>説明文</p>
    </article>
  </section>
</template>

<script>
  export default {
    
  }
</script>

<style scoped>
.mangas {
  display: flex;
  flex-flow: row wrap;
}

.manga {
  box-sizing: border-box;
  width: 280px;
  padding: 8px;
  border: 1px solid #ccc;
  box-shadow: 0 2px 2px #aaa;
}

</style>