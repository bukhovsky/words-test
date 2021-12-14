<template>
  <div>
      <button> {{msg}}</button>

  </div>
</template>

<script>
export default {
  name: 'Button1',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
div {
  color: blue;
}

</style>
