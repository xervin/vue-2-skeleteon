<template>
  <div>
    <h2 class="hello-world">Hello World!</h2>
    <h3 class="example">Example: {{ example }}</h3>
  </div>
</template>

<style lang="scss" src="./app.scss"></style>

<script>
export default {
  data() {
    return {
      example: 'example!'
    }
  }
}
</script>