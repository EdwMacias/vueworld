<template>
  <NavBar/>
  <h1>Lista de posts</h1>
  <div class="container-fluid text-bg-dark p-3">
    <CounterComposition/>
  </div>
  <PostContainer/>

</template>

<script lang="ts" setup>
// import NavBar from "./components/NavBar.vue";
import PostContainer from './components/PostContainer.vue';
// import "bootstrap/dist/css/bootstrap.min.css";
// import "bootstrap/dist/js/bootstrap.min";
import CounterComposition from './components/CounterComposition.vue';
</script>


<style>
h1{
  color: #5F5F5F;
}
</style>
