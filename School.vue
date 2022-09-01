<template>
  <div>
    <h1 class="myStyle">我是{{name}}</h1>
  </div>
</template>

<script>
export default {
    name:'Student',
    data() {
        return {
            name:'School'
        }
    },
}
</script>

<style>
.myStyle{
    color: skyblue;
}
</style>