<template>
<div class="post-card">
    <h3>Hola vue</h3>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi alias corrupti ad perferendis quidem blanditiis consequatur ex reprehenderit deleniti labore nulla, hic vel numquam enim aut delectus earum obcaecati odit!</p>
    <PostButton/>   
</div>
</template>

<script lang="ts" setup>
import PostButton from "./PostButton.vue";
</script>

<style>
.post-card{
    border-radius: 15px;
    padding: 10px;
    margin: 5px;
    border: 1px solid #ccc;
}
</style>