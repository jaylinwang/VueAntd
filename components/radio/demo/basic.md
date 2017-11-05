### 基本用法

::: demo

```html
<template>
<div>
  <v-radio v-model="v1" :label="1" @change="v1Change">
    选项1
  </v-radio>
</div>
</template>
<script>
let script = {
  data () {
    return {
      v1: ''
    }
  },
  methods: {
    v1Change () {
      console.log(this.v1)
    }
  }
}
export default script
</script>
```

:::