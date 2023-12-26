<template>
  <div>
    <!-- Your component's template goes here -->
  </div>
</template>

<script>
import { onMounted } from 'vue'

export default {
  name: 'MyComponent',
  setup() {
    onMounted(() => {
      window.location.href = 'http://www.barainvest.com'
    })
  }
}
</script>
