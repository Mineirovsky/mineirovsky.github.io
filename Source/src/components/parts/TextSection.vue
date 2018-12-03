<template>
  <div>
    <h2 id="SectionTitle">{{ title }}</h2>
    <article>
      <slot></slot>
    </article>
  </div>
</template>

<script>
export default {
  name: 'TextSection',
  props: {
    title: String
  }
}
</script>

<style scoped>

</style>
