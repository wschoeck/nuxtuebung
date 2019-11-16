<template>
  <div class="Section">
    <h2 class="Section__title">{{ title }}</h2>
    <div class="Section__content">
      <slot></slot>
    </div>
  </div>
</template>

<script>
export default {
  props: ['title']
}
</script>

<style>

.Section__title {
  background-color: red;
}

</style>
