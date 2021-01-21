<template>
  <div id="app">

    {{$store.state.name}}
    {{$store.state.a.name}}
    {{$store.state.b.name}}
    <button @click="$store.commit('changeName')">点击</button>
    <button @click="$store.commit('a/changeName')">changeA</button>
  </div>
</template>

<script>

export default {
  name: "App",
  
};
</script>

<style>

</style>
