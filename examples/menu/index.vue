<template>
<div>
  <h2>dark</h2>
  <dark></dark>
  <h2>basic</h2>
  <basic></basic>
  <h2>default</h2>
  <defaultValue></defaultValue>
  <h2>horizontal</h2>
  <horizontal></horizontal>
  <h2>vertical</h2>
  <vertical></vertical>
</div>
</template>

<script>
import basic from './basic.vue'
import defaultValue from './default.vue'
import horizontal from './horizontal.vue'
import vertical from './vertical.vue'
import dark from './dark.vue'

export default {
  components: {
    basic, defaultValue, horizontal, vertical, dark
  }
}
</script>
