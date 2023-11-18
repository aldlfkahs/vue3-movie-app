<template>
  <div class="test">
    {{ movie.imdbID }}
  </div>
</template>


<script>
export default {
  props: {
    movie: {
      type: Object,
      default: () => ({})
    }
  }
}
</script>