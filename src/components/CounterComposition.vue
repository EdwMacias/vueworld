<template>
    <div>
        <h4>{{ counter }}</h4>
        <button @click="addCounter" class="btn btn-success">incrementando</button>
    </div>
</template>

<script lang="ts" setup>
import { ref } from 'vue';
    let counter = ref(0)
    const addCounter = () => {
        counter.value++;
    }
</script>