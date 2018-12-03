<template>
  <div class="hello">
    <text-section title="Who am I">
      I am a Computer Science student
    </text-section>
  </div>
</template>

<script>
import TextSection from '@/components/parts/TextSection'

export default {
  name: 'HelloWorld',
  components: { TextSection }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
