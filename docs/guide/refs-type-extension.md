# `refs` Type Extension

```vue
<script lang="ts">
import Vue from 'vue'
import Component from 'vue-class-component'

@Component
export default class InputFocus extends Vue {
  // annotate refs type
  $refs!: {
    helloComponent: Hello
  }
}
</script>
```