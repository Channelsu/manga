<template>
  <section class="single-manga">
    <h1>{{ $route.params.id }}</h1>
    <div>
      <img src="" alt="">
    </div>
    <p>マンガの詳細</p>
  </section>
</template>

<script>
  export default {
    
  }
</script>

<style scoped>
.single-manga {
  display: flex;
  flex-flow: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 30px;
}

</style>