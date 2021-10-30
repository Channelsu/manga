<template>
  <div>
    <h1>マンガ</h1>
    <div v-for="manga in mangas" :key="manga.id">
      {{ manga.name }}
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      mangas: [
        { id: '1', name: 'ONE PIECE' },
        { id: '2', name: 'キングダム' },
        { id: '3', name: 'ホイッスル' },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
</style>
