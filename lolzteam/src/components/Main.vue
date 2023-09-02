<template>
  <Header></Header>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>
<!--Импоритируй header.scss-->


<style>
@import 'header.scss'
</style>
