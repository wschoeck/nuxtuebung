<template>
  <div class="container">
    <Section title="Inhalt">
      hjnjgsjss
    </Section>

    <h1>{{ level }}</h1>
    <Skill title="Design" level="90" />
    <Skill title="Code" level="50" />
    <Skill title="Management" level="70" />
    ...
  </div>
</template>

<script>
import Skill from '~/components/Skill.vue'
import Section from '~/components/Section.vue'

export default {
    components: {
      Skill,
      Section
    }
}
</script>

<style>
.container {
  margin: 0 auto;
}

</style>
