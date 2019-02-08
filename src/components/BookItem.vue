<template>
    <li>{{book.title}}:{{book.author}}</li>
</template>

<script>

</script>
export default {
  name: 'BookItem',
  props: ['book'],
}
<style>
li {
  display: block;
  margin: 0 10px;
}
</style>
