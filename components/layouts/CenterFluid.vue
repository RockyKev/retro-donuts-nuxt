<template>
  <section class="container-fluid">
    <div class="row text-center">
      <div class="mx-auto" :class="column">
        <slot></slot>
        <!-- <slot name="image"></slot> -->
      </div>
    </div>
  </section>
</template>

<script>
export default {
  props: ['column']
}
</script>

<style scoped>
/* h3 {
  font-family: Fira Sans;
  font-style: normal;
  font-weight: bold;
  font-size: 48px;
  line-height: 58px;
} */
</style>
