<template>
  <section class="container">
    <div class="row">
      <div class="col-12 col-md-6">
        <slot name="image"></slot>
      </div>

      <div class="col-12 col-md-6">
        <slot name="header"></slot>
        <slot name="paragraph"></slot>
      </div>
    </div>
  </section>
</template>

<script>
// export default {
//   props: ['left', 'right']
// }
</script>

<style scoped>
</style>
