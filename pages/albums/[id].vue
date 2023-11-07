<script setup lang="ts">
const route = useRoute()

// When accessing /albums/123, route.params.id will be 123
let album_id = route.params.id
</script>

<template>
    <div>
      Edit album for id {{ album_id }}
    </div>
</template>
  