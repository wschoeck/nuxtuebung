<template>
  <div class="Skill">
    <h3 class="Skill__title">{{ title }}</h3>
    <div class="Skill__background">
      <div class="Skill__level" :style="{ width: level + '%' }">
        {{ level }}%
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: ['title', 'level']
}
</script>

<style>
.Skill__background {
  background-color: #cccccc;
  padding: 4px;
}
.Skill__level {
  background-color: #5f7b9c;
}
</style>
