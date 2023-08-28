<template>
    <h1 v-if="age < 18 ">Eres menor de edad</h1>
    <h1 v-else>Eres mayor de edad</h1>
</template>

<script lang="ts" >
import {  defineComponent } from 'vue';
    export default defineComponent ({
        name:'exampleSelective',
        setup(){
            let age = 17
            return {age}
        }
    })
</script>

<style scoped>

</style>