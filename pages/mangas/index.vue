<template>
  <section class="mangas">
    <article class="manga">
      <div class="thumbnail" style="background-image: url(https://cdn-scissors.gigaviewer.com/image/scale/b6e24b6a28f7e90515663c0055534678c962168e/enlarge=0;height=484;no_unsharpmask=1;quality=90;version=1;width=484/https%3A%2F%2Fcdn-ak-img.shonenjumpplus.com%2Fpublic%2Fseries-thumbnail%2F10833519556325021853-84c0dbccc6b51dbff40781c7a6621ae1%3F1635721960)"></div>
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

.thumbnail {
  background-position: center;
  background-size: cover;
  width: 100%;
  height: 200px;
}

</style>