<template>
  <p>{{ text }}</p>
  <button @click="change">измени текст</button>
  <button @click="change2">измени текст2</button>
</template>

<script>
export default {
  data(){
    return{
      text: "что-то"
    }
  },
  methods: {
    change(){
      this.text = "ничего нет"
    },
    change2(){
      this.text = "ничего"
    }
  }
}
</script>

<style>

</style>
