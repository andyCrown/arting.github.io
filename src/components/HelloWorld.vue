<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
<!--  <div id = 'vue_det'>
    <h1>site:{{site}}</h1>

  </div> -->
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: '世界和平！',
      site:'123456'
    }
  }
}
</script>
