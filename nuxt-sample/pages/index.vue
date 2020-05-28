<template>
<Button class="alert-button"/>
</template>

<script>
import Button from '~/components/Button.vue'

export default {
  components: {
    Button
  }
}
</script>

<style scoped>
.alert-button {
  background-color: red;
  font-size: 20px;
}
</style>
