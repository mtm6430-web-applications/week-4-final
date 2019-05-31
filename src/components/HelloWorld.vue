<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>{{ content }}</p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data: function () {
    return {
      content: 'This is our first Vue App using Vue CLI'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

</style>
