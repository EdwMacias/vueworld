<template>
    <div>
        <h3> Contador {{ counter }}</h3>
        <button v-on:click="addCounter" class="btn btn-danger">Incrementar</button>
    </div>
</template>

<script lang="ts">
    import { defineComponent } from 'vue';
    export default defineComponent({
        name: 'CounterOption',
        
        data() {
            let counter = 0;
            return {counter};
        },
        methods: {
            addCounter(){
                this.counter++
            }
        }
    })
</script>

<style>

</style>